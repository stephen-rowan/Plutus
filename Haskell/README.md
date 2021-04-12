# Haskell README


# Plutus Pioneer Program - GitHub

[Plutus Pioneer Program - GitHub](https://github.com/input-output-hk/plutus-pioneer-program?utm_source=Developers&utm_campaign=d588ea48f0-EMAIL_CAMPAIGN_2021_03_31_06_14_COPY_01&utm_medium=email&utm_term=0_c9c99d4ad3-d588ea48f0-77574941)

Guides :

https://gutier.io/post/development-installing-haskell-quick-and-easy/


# Haskell

## Haskell Installation

https://www.haskell.org/platform/linux.html#linux-ubuntu

 `sudo apt-get install haskell-platform`

## Version Issue ?

I have installed the haskell-platform that haskell.org recommends on ubuntu (e.g., sudo apt-get install haskell-platform) - I checked the ghc version (ghc --version) and returned version 8.8.5. I noticed Lars recommends version 8.10.2 (https://discordapp.com/channels/826816523368005654/826836848520200233/829303281184145468). 
Is there a ubuntu repository for haskell-platform that includes this newer version? Or will have to install the package elements separately from source?

## Plutus Installation

Discord context :

https://discordapp.com/channels/826816523368005654/826822689427554365/829287046882525214

https://www.reddit.com/r/CardanoDevelopers/comments/majuba/plutus_playground_on_a_local_machine/

## Plutus Platform GitHub

https://github.com/input-output-hk/plutus

### Install Nix

https://nixos.org/download.html

The quickest way to install Nix is to open a terminal and run the following command (as a user other than root with sudo permission):

`$ sudo curl -L https://nixos.org/nix/install | sh`

Make sure to follow the instructions output by the script.

The installation script requires that you have sudo access to root.

### Clone Plutus

https://github.com/input-output-hk/plutus.git

`cd plutus root`

### How to build the Haskell packages and other artifacts

How to build Haskell packages and other artifacts with Nix

Run `nix build -f default.nix plutus.haskell.packages.plutus-core.components.library` from the root to build the Plutus Core library.

### Starting Plutus Playground

https://tutorials.cardanoacademy.io/setting-up-plutus-playground/starting-plutus-playground#access-to-your-playground

cd plutus
nix-shell



