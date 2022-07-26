# SoN Timesheet

Name: Atharva (wiredhikari)

## 2022-07-18 -- 2022-07-24

Hours: 40

**Meetings:**

 * Kickoff meeting 1
 * Team Meetings
 * Jitsi project meeting

**Learning:**

 * History of Nix
 * Packaging Python
 * Read about Nix Flakes
 * Jitsi and Nix

**Worked on packages:**

* Build Transparency (Trustix)
    * Triaged the software
    * Pair Programmed for this
    * Fixed Overlay Issue
* Weblete 
    * Tested and Reviewed the package
* General Triage
    * Took a look at issues in `ngi-nix/ngi` 


## 2022-07-25 -- 2022-07-31

Hours: 37

**Meetings:**
* Team Meetings
* Pair Programming with teammates
* Public Lecture: History of Nix


**Learning:**

* Read about Hydra workflow
* Cachix
* History of Nix
* Packaging Rust Modules

**Worked on packages:**

* Rust-Threadpool
    * Triage 
    * Discussed on how lib works in rust and closed the issue
* Editoria
    * Fixing NodeJS issue by migrating version from 12 to 14
    * Pair Programmed to create a Nix Package 
* Sipexer
    * Triage of the package
    * Started working on packaging it.
* Cryptolyzer
    * Triage 
    * Worked on writing a flake for Cryptoparser

## 2022-08-01 -- 2022-08-07

Hours: 42

**Meetings:** 
* Public Lecture: The Architecture and History of Nixpkgs
* Pair programming


**Learning:**
* Carnix and Crate2nix
* BuildGoPackage
* Deepdive into Overlays
* Nixpkgs architecture 

**Worked on packages:**
* Sipexer
    * Upstreamed and closed the issue
* Cryptolyzer
    * Worked on flakifying Cryptolyzer
    * Added cryptoparser subflake in Cryptolyzer
    * Got it reviewed and tested. Closed the issue.
* Wireguard
    * Triage 
    * Worked on migrating buildRustPackage to crate2nix in the current flake. 
* Sylk Suite
    * Triage and breakdown of components that need packaging.

## 2022-08-08 -- 2022-08-14

Hours: 41

**Meetings:**

* Team meeting
* Pair programming session
* Public Lecture: Flattening the Learning Curve

**Learning:**
* Jitsi Ecosystem
* Nixos-Container
* Cross Compilation
* Packaging Ocaml Modules

**Worked on packages:**

* ocaml-psi
    * Triage 
    * Started working on making a [flake](https://github.com/p2pcollab/ocaml-psi) 
* Fractal
    * Helped Yeurien in triaging and creating a nix flake for the nightly version
* Sylk Server
    * Pair Programmed on packaging some dependencies

## 2022-08-15 -- 2022-08-21

Hours: 38

**Meetings:**
* Mob Programming Session
* Weekly Team session
* Pair Programmed with teammates
* Public Lecture: Nix Is Going Mainstream


**Learning:**
* Using flakes with cargo2nix and carnix
* Build systems around ocaml 
* Building autotools packages and patching


**Worked on packages:**
* Documentation of [nixos-container](https://github.com/ngi-nix/ngi/issues/296)
    * Used nixos-containers and made schema for documentation 
*  ocaml-psi
    * Made a sub-flake for bloomf dependency
* NLNet packages
    * Triage on Rust based packages.
* Fractal (Pair Programmed)
    * Worked on the flake for the nightly version: https://github.com/ngi-nix/fractal

## 2022-08-22 -- 2022-08-28

Hours: 30

**Meetings:**
* Public Lecture: Hydra, Nix's CI
* Weekly Team session
* Pair Programming with Yureien

**Learning:**
* Hydra, Nix's CI
* Implementing Cachix in Github Actions


**Worked on packages:**
* Sylk Mobile
  * Package [python3-otr](https://github.com/NixOS/nixpkgs/pull/188015)
* GNUNet Messenger
    * Triage
* Entire SiP Stack
    * Pair Programmed in packaging OpenSIPS.
    * Helped in Packaging some dependencies.
  
## 2022-08-29 -- 2022-09-04

Hours: 40

**Meetings:**
* Weekly Team session
* Michiel Leenaars - The Significance of Reproducible Software in International R&D 
* Pair Programming with a-kenji
* Pair Programming with Yawar
* Pair Programming with Yurein

**Learning:**
* Testing nixos-containers
* How documentation in Nix toolchains work
* Mob Programming

**Worked on packages:**

* NixOS-Container
  * Continued Documentation of [nixos-container](https://hackmd.io/4bVSA0uWTPGEh9ZN54fGbQ)

* Waasabi
  * General Triage
  * Worked on the [issue](https://github.com/ngi-nix/ngi/issues/256) (not completed yet)

* Etherpad
  * Pair Programmed with yawar
  * Used dream2nix and flakes to package [etherpad](https://github.com/ngi-nix/Etherpad_nix/blob/master/flake.nix)

* ocaml-psi
  * Wrapped up the pending work
  
* Sylk Server
  * Bugfixes in the PR

## 2022-09-05 -- 2022-09-18

Hours: 20

**Meetings:**

* Meeting with a-kenji
* Pair Programming
* John Ericson's Nix x IPFS talk
* Konrad Hinsen - Nix/Guix and Reproducible Science

**Learning:**

* Running nix-darwin with `OSX-KVM`
* NodeJS on Nix
* Gitlab actions for cachix

**Worked on packages:**

* NextCloud
  * General Triage
  * Curated the schema and list of packages needed to be packaged
  * Will be completed post Summer of Nix
  
* GNUNet Messenger
  * General Triage
  * Work now taken care by @cab404 and @nunop 

* NixOS-Container
  * Continued Documentation of [nixos-container](https://hackmd.io/4bVSA0uWTPGEh9ZN54fGbQ)

## 2022-09-19 -- 2022-09-30

Hours: 30

**Meetings:**
* Pair Programming with Yureien
* Luc Perkins - Real World DevOps with Nix
* Connor Brewster - The Road to Nix at Replit 

**Learning:**
* crate2nix
* Github Actions for rust based packages

**Worked on packages:**

* Sylk Server
  * Bug Fixes and Improvements

* Wiredguard Rust Implementation
  * Schema for Github Actions

* Wrapping up issues and creation of timesheet

* Triage of Left Packages, will be completed in upcoming weeks
 
