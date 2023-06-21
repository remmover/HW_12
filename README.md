# Address Book

This is a simple address book program implemented in Python. It allows you to store and manage contacts with their names and phone numbers. Additionally, you can add birthdays to contacts and calculate the number of days remaining until their next birthday.

## Features

- Add a new contact with a name and phone number.
- Add a birthday to a contact and calculate the days remaining until the next birthday.
- Change the phone number of an existing contact.
- Retrieve the phone number of a contact by searching for their name or phone number.
- Display all contacts stored in the address book.
- Save the address book to a binary file for future use.

## Getting Started

To use this address book program, follow these steps:

1. Clone the repository to your local machine.
2. Make sure you have Python installed (version 3.6 or higher).
3. Run the program by executing the `address_book.py` file: `python address_book.py`.
4. You can now interact with the address book by entering commands in the console.

## Usage

The address book program supports the following commands:

- `hello`: Displays a greeting message.
- `add <name> <phone> [birthday]`: Adds a new contact with the given name and phone number. Optionally, you can provide a birthday in the format "dd.mm.yyyy".
- `change <name> <phone>`: Changes the phone number of an existing contact with the given name.
- `phone <query>`: Searches for contacts by name or phone number and displays their phone numbers.
- `show all [count]`: Displays all contacts stored in the address book. Optionally, you can specify the number of records to show at once.
- `help`: Displays a help message with the list of available commands.
- `good bye`, `close`, `exit`: Exits the program and saves the address book to a binary file.

Note: The commands and input are case-insensitive.

## Examples

- To add a new contact: `add John Doe +380123456789`.
- To add a contact with a birthday: `add Jane Smith +380987654321 25.12.1990`.
- To change the phone number of a contact: `change John Doe +380111111111`.
- To search for a contact: `phone John`.
- To display all contacts: `show all`.
- To exit the program: `exit`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
