# nix-dev

(Planned) Tool for working on multiple packages that depend on eachother. Based on https://nixos.org/.

# Basic workflow

TODO: specifics

1. Create a directory for a project
2. Create a dev.nix file describing which packages you want to work on
3. `nix-dev build`
4. hack on the source
5. `nix-dev build`
6. test
7. go to 4.
