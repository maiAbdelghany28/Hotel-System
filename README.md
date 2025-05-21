########################################################
##           Hotel Management System in C++           ##
########################################################

## Author
Mai Waheed AbbdelGhany

## Project Overview

This is a simple command-line hotel management system written in C++. It allows hotel staff to manage room bookings, guest check-ins and check-outs, search for guest information, and generate summary reports.


## Features

- Room management (Single/Double room setup)
- Guest check-in and check-out
- Display of available rooms
- Guest information search
- Summary report for income and total bookings
- Payment calculation per guest
- Delete all hotel records

## Menu Options

After starting the program, the user is presented with a menu:
1. Check in  
2. Get available rooms  
3. Search information of a specific guest  
4. Get guests summary report  
5. Make payment for a guest  
6. Check out  
7. Delete all records  
8. Exit program  

## How It Works

1. The user is prompted to input the total number of rooms.
2. Half the rooms are assigned as **single**, and the other half as **double**.
3. The system initializes and waits for user commands via the menu.
4. Each operation interacts with internal arrays of `Room` and `Guest` structs.

## File Structure

- `HotelSystemProject.cpp` — The main source file containing:
  - `Room` and `Guest` structures
  - `Hotel` class for encapsulating hotel operations
  - `main()` function for CLI interaction loop

## Pricing

- **Single room:** 1000 per day  
- **Double room:** 2000 per day

## ⚠ Limitations

- Only 100 guests are supported.
- Data is not persisted — everything is stored in memory and lost when the program ends.
- Input validation is minimal (e.g., assuming correct types entered).

## Running the Program

1. Compile the code using a C++ compiler like g++:
   ```bash
   g++ -o HotelSystem HotelSystemProject.cpp
