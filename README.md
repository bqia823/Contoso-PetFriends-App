# Contoso PetFriends App

## Overview
The Contoso PetFriends App is a simple console-based application designed to manage and display information about pets in a shelter. The application allows users to list all current pets and search for dogs based on specified characteristics.

## Technical Design
- **Programming Language**: C#
- **Framework**: .NET Core
- **Data Storage**: In-memory 2D string array

## Features
1. **List All Pets**: Displays all information about the pets currently stored in the system.
2. **Search Dogs by Characteristics**: Allows users to search for dogs based on multiple characteristics.

## Code Explanation

### Data Storage
The data for each pet is stored in a 2D string array called `ourAnimals`. Each row represents a pet, and the columns store the following information:
- ID
- Species
- Age
- Nickname
- Physical Description
- Personality Description
- Suggested Donation

### Sample Data
The sample data is initialized in the `for` loop where each pet's information is hardcoded for demonstration purposes.

### Menu Options
The main menu allows the user to:
1. List all pets.
2. Search for dogs by characteristics.

## How to Run

### Prerequisites
- .NET SDK installed
- A console to run the application

### Steps to Run
1. **Clone the repository or download the source code.**
2. **Navigate to the directory containing the source code.**
3. **Run the application using the following command:
 ```sh
dotnet run
