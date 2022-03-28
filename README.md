# Morse Project
## _Simple Morse Audio File Maker_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Features
- Define the input string
- Define the input frequency (400 by default)

## Used Library
I use [this beautiful library](https://github.com/nlohmann/json) that makes possible to use JSON file. 

## Installation
Download this git repository and open it with your favorite IDE.
Otherwise you can use the Releases versions :)

## How to use
### In your terminal
```sh
./morse --text "test" -freq 600
```
### Result
Open the audio file (with your favorite song software, here VLC)
```sh
vlc result.wav
```