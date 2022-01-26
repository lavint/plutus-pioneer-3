# plutus-pioneer-3

## Prerequisite 
* **Make sure you have cloned [plutus-apps](https://github.com/input-output-hk/plutus-apps) and [plutus-pioneer-program](https://github.com/input-output-hk/plutus-pioneer-program) in the same folder**

* **Make sure you have setup `nix` and `cabal` following the steps in [plutus-apps](https://github.com/input-output-hk/plutus-apps)**

<br>

## Week 1 - Set Up Plutus Playground

In terminal,

1. `cd plutus-pioneer-program/code/week01`

1. `less cabal.project` to find the git version for the week. Use the tag that has playground-common in subdir.

1. `:q` to exit

1. `cd ../../../plutus-apps`

1. `git checkout 41149926c108c71831cfe8d244c83b0ee4bf5c8a`

1. `nix-shell`

1. `cd plutus-playground-client && plutus-playground-server` to start a server

Open a new terminal and make sure you are in plutus-apps repo,

1. `nix-shell`

1. `cd plutus-playground-client && npm start` to start a client

Open `https://localhost:8009/` in a browser to use the playground

<br>

To checkout the documentation,

1. `cd plutus-apps `

1. `nix-shell`

1. `build-and-serve-docs`

<br>
<br>
<br>

## Week 2 - Set Up Plutus Playground

`git checkout 6aff97d596ac9d59460aab5c65627b1c8c0a1528`

To check and compile Haskell:

1. `cd plutus-apps `

1. `nix-shell`

1. `cd` to the folder that contains the `cabal.project` file

1. `cabal repl`

1. `:l file.hs` to load file

1. `:r` to reload file


<br>
<br>
<br>


## Resources

[plutus-apps](https://github.com/input-output-hk/plutus-apps)

[plutus-pioneer-program](https://github.com/input-output-hk/plutus-pioneer-program)

[Plutus Community Documentation](https://docs.plutus-community.com/)

[Plutus Starter Pack](https://docs.google.com/document/d/13112LHG9vVvNUs40oZSqZ-DF6_yFiT_SJZ2NaEmjMM4/edit?usp=sharing)

