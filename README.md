# Hotel Reservation System

The Hotel Reservation System is a Python project that allows users to book hotels and spa packages using a command-line interface. It utilizes data from CSV files to manage hotel information, credit card validation, and booking reservations.

## Prerequisites

Before running the program, make sure you have the following dependencies installed:

- Python 3
- pandas library

You can install the required dependencies using pip:


## Getting Started

1. Clone the repository or download the project files.
2. Place the `hotels.csv`, `cards.csv`, and `card_security.csv` files in the same directory as the Python scripts.
3. Open a terminal or command prompt and navigate to the project directory.

## Usage

To use the Hotel Reservation System, follow these steps:

1. Run the `hotel_reservation.py` script using the following command:

To use the Hotel Reservation System, follow these steps:

1. Run the `hotel_reservation.py` script using the following command:
`python hotel_reservation.py`
2. Enter the ID of the hotel you want to book when prompted.

3. If the hotel is available, you will be asked to provide credit card details for payment.

4. Enter the credit card number, expiration date, holder's name, and CVC when prompted.

5. If the credit card information is valid, you will be prompted to enter a password for authentication.

6. If the password is correct, the hotel will be booked, and you will be asked to enter your name for the reservation.

7. A reservation ticket will be generated and displayed, showing your booking data.

8. You will be asked if you want to book a spa package. Enter 'yes' or 'no' accordingly.

9. If you choose to book a spa package, a separate reservation ticket for the spa will be generated and displayed.

10. Finally, you will receive a confirmation message for your hotel reservation.

## File Descriptions

- `hotel_reservation.py`: The main script that handles the hotel reservation process.
- `hotels.csv`: CSV file containing hotel information, including IDs, names, and availability.
- `cards.csv`: CSV file containing credit card details for validation.
- `card_security.csv`: CSV file containing secure credit card details for authentication.
- `README.md`: This file, providing an overview of the project and instructions for usage.

## Notes

- The hotel reservation system uses CSV files to store and retrieve data. Make sure the CSV files are formatted correctly and placed in the project directory.

