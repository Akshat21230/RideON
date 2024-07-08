
# RideOn

RideOn is a DBMS project that simulates a ride-sharing service. This project includes a Python script to manage and interact with a MySQL database, offering various functionalities related to drivers, customers, and rides.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [Contributing](#contributing)
- [License](#license)

## Introduction

RideOn is designed to help users manage and interact with a ride-sharing service database. It offers functionalities such as displaying available drivers, showing drivers with ratings above 3, printing details of rental stands in specific cities, and more.

## Features

- Display available drivers.
- Show drivers with ratings above 3.
- Print the number of rental stands in a particular city or place.
- Print details of the top 10 drivers with respect to ratings.
- Provide a way to address unclear addresses.
- Calculate and display money spent by each customer monthly in a year.
- Trigger a journey start.

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/RideOn.git
    cd RideOn
    ```

2. **Install the required Python libraries**:
    ```sh
    pip install mysql-connector-python pandas tabulate
    ```

3. **Set up the MySQL database**:
    - Make sure you have MySQL installed and running.
    - Update the database connection parameters in the script (\host\, \user\, \passwd\) as per your MySQL setup.

## Usage

1. **Run the script**:
    ```sh
    python3 RideOn.py
    ```

2. **Follow the on-screen menu options to interact with the database**.

## Functions

### welcome()

Displays a welcome message with the RideOn ASCII art.

### menutour()

Displays a menu with the following options:
- Show available drivers
- Show drivers with ratings above 3
- Print the number of rental stands in a particular city/place
- Print details of the top 10 drivers with respect to ratings
- Handle unclear addresses
- Display money spent by each customer monthly in a year
- Trigger a journey start
