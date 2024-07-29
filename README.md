# Inter-Planetary File System

Welcome to the Inter-Planetary File System (IPFS) project!

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)

## Introduction
The IPFS project is designed to simulate a distributed file storage system inspired by the InterPlanetary File System (IPFS). This project includes functionalities for hashing files, managing machine nodes in a circular linked list, and providing a B-tree structure for efficient file management.

## Features
- SHA-1 Hashing of file contents and machine names.
- Circular linked list for machine nodes.
- B-tree implementation for file storage.
- Using Windows.h library to modify folders and files on your local PC

## Requirements
- g++ compiler to compile files
- Crypto++ library for cryptographic functions
- Also go to the RoutingMachine.cpp and change the location of the folder where all the files would be saved

## Installation
### Install Crypto++ Library
1. Download and install the Crypto++ library from [Crypto++](https://cryptopp.com/).
2. If having difficulty in doing it, follow this YouTube guide. (https://www.youtube.com/watch?v=5XE4zEN-WKg).

### Compile the Project
Navigate to the project directory and use the following command to compile the project:
g++ -o ipfs main.cpp RoutingMachine.cpp hashing.cpp B-Trees.cpp -lcryptopp

### Executing the Project
./ipfs
