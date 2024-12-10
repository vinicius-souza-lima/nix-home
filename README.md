Install nix and run these commands:

```sh
nix run nixpkgs#gh -- auth login
nix run nixpkgs#gh -- auth login
nix run nixpkgs#gh -- repo clone vinicius-souza-lima/nix-home
nix run home-manager -- switch --flake nix-home#vinicius
```