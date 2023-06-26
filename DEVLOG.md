


## setup nix based development environment 

- installed nix the better way: https://github.com/DeterminateSystems/nix-installer#the-determinate-nix-installer
  - filed issue about wrong installer version: https://github.com/DeterminateSystems/nix-installer/issues/529 
  - `reboot`; `nix upgrade-nix`

- basic shell flake & direnv: https://github.com/tweag/rules_nixpkgs/blob/master/guide.md
  - installed nix-direnv: https://github.com/nix-community/nix-direnv#from-source (/-/sys/module/nix-direnv)
  - `nix flake init`
  - edit flake 
  - `nix flake update`
	