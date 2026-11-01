# Budget Tracker

Java command-line tool that allows users to input each expense and track the remaining budget after each transaction occurs.

## The Problem

When I go on trips with my family and friends, I usually keep track of all my money spent by collecting the bills or keeping track on the notes app. As a result, I often forget to track a few transactions that occurred or lose track completely which causes me to spend more than I initially wanted too. I want to solve this problem so that I do not go above the budget that I set. 

## How It Works

- Java command-line tool that allows users to input their expenses and see the remaining budget
- User input is appended to the CSV file 
- File is read and remaining budget is calculated and then printed out

[System diagram](docs/diagram.png)

## Tech Stack

- **Language:** Java
- **Libraries:** java.io.FileWriter, java.io.PrintWriter, java.io.BufferedReader, java.io.FileReader
- **External tools:** None

## Setup

```bash
git clone https://github.com/krishashah/CS193-FinalProject.git
cd CS193-FinalProject
```

## Usage

java -cp src Main

## Roadmap

- Split the budget into categories 
- User enters which category they spent money in 
- Summary of money remaining in each category is printed out for the user to see 

## Author

Krisha Shah, https://github.com/krishashah
