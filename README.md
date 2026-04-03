# Multithreaded File Transfer System (C++ / TCP/IP)

## Overview
This project is a client-server file transfer system built in C++ using TCP/IP sockets. It supports communication between a client and server and will be extended to handle concurrent connections.

## Features
- TCP socket communication
- Client-server architecture
- Message exchange between client and server

## Technologies
- C++
- Linux (WSL)
- TCP/IP sockets

## How to Run

### Compile:
g++ server/server.cpp -o server_app -pthread  
g++ client/client.cpp -o client_app  

### Run:
./server_app  
./client_app  
