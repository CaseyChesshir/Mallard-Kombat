# README #

This README documents the steps necessary to get our application up and running.

### What is this repository for? ###

* Holds the source code and media necessary to make Mallard Kombat

### How do I get set up? ###

* Summary of set up: 
* The easiest way would be to install the SDL dependencies via Homebrew if you're on OS X. 
* Just go for the following commands after you have Homebrew:
* brew install SDL2
* brew install SDL2_image
* brew install SDL2_Mixer
* brew install SDL2_ttf
* Dependencies: SDL2, SDL_image, SDL_mixer, SDL_ttf

### Contribution guidelines ###

* Pull this code all you want. Modify it however you see fit. I'd prefer if you told me just for my curiosity's sake but go for it.

### Who do I talk to? ###

* Repo owner or any of the admins

### Structure of the program ###

* duck.cpp:
holds the data for the player's duck object

* mallard.cpp:
holds most of the main game code

* main.cpp
invokes mallard and executes main game loop 

* beaver.cpp:
our first enemy hails from OSU and served as a base to design others

* husky.cpp
enemy based on the UW husky mascot

* trojan.cpp
slow moving enemy from USC

* enemy.hpp
allows us to abstract all of the things that an enemy needs

* Makefile
compiles all the code together. just run make in the terminal, then ./mallard# Mallard-Kombat
