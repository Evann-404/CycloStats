# CycloStats

CycloStats is a lightweight console-based application designed to help cyclists track their rides and manage bike maintenance efficiently.

## Features

- **Ride Tracking**
  ==> Log rides with distance, elevation gain, location, and date

- **Bike Maintenance**
  ==> Track cost, description, and type of maintenance

- **Local Storage with SQLite**
  ==> All data is saved locally (easy to back up or inspect)

## Tech stack

- **Language**: C++
- **Database**: SQLite
- **Schema**: Designed using [dbdiagram.io](https://dbdiagram.io)
- **Dependencies**: SQLite3 development libraries

## Database Schema
![DATABASE-SCHEMA](assets/db-schema.png)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Evann-404/CycloStats.git
   cd cyclostats
   ```
2. Build (requires SQLite3 development package):
   ```bash
   g++ -o cyclostats main.cpp -lsqlite3
   ./cyclostats
   ```
