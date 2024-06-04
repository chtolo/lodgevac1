# Lodge Vac Project

This project is a simple vacation lodge booking system. It includes two tables: 'users' and 'reservations'.

## Table: Users

The 'users' table has the following fields:
- userid (unique identifier for each user)
- name (full name of the user)
- email (email address of the user)
- password (securely stored user password)

## Table: Reservations

The 'reservations' table has the following fields:
- email (email address of the user, links to the 'users' table)
- nom-maison (name of the vacation lodge)
- nombre_personne (number of people in the booking)
- nombre_nuit (number of nights in the booking)
- date (date of the booking)

## Installation

To install the necessary dependencies for this project, use the following command:

```
pip install -r requirements.txt
```

This command will install all the libraries listed in the 'requirements.txt' file.

## Usage

To run the project, use the following command:

```
python app.py
```

This command will start the server and you can access the project at `http://localhost:5000` (or the port number specified in your `app.py` file).

Please ensure that you have Python and pip (Python's package manager) installed on your system before proceeding with the above steps.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

