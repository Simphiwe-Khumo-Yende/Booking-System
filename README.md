# Coding Clinic Booking System

Welcome to the Coding Clinic Booking System! This command-line toolset automates the booking process for Coding Clinic sessions. With this system, students can easily book, view, and manage their clinic sessions, while volunteers can indicate their availability to assist others.

## Contributors
- Simphiwe Yende
- Sikho Qangule
- Mpumelelo Msane
- Nomonde Bhengu

## Installation

To set up the Coding Clinic Booking System on your Linux workstation, follow these steps:

1. Clone this repository to your local machine:

```
git clone <repository-url>
```

2. Navigate to the project directory:

```
cd coding-clinic-booking-system
```

3. Make the setup script executable:

```
chmod +x setup.sh
```

4. Run the setup script:

```
./setup.sh
```

This script will install all dependencies and configure the system for first-time use.

## Usage

This program can be executed from anywhere on the terminal by running `booking-app`. Here's how to navigate through the app:

1. When you run `booking-app`, you'll be presented with a menu to choose an action:
    - Configure the system
    - View calendars
    - Book a slot
    - Volunteer for a slot
    - Cancel a booking
    - Cancel volunteering
    - Exit the application

2. Use the arrow keys to navigate up and down the menu options.
3. Press `Enter` to select an option.
4. Follow the prompts and instructions to complete the selected action.

## Features

- **Configure the System**: Easily configure the system to connect to WeThinkCode_ and Coding Clinic Google calendars.
- **View Calendars**: View upcoming bookings for the next 7 days.
- **Make a Booking**: Book a slot for a Coding Clinic session.
- **Volunteer for a Slot**: Students can volunteer their time to assist others.
- **Cancel Booking**: Cancel a booked session.
- **Cancel Volunteering**: Withdraw availability as a volunteer for a specific slot.

## APIs and Dependencies Used

- Google Calendar API: Used to interact with WeThinkCode_ and Coding Clinic Google calendars.
- Python `enquirepy` library: Used for creating interactive command-line interfaces.
- Python `requests` library: Used for making HTTP requests.
- Python `arrow` library: Used for handling dates and times.
- Shell scripting: Used for setup and configuration tasks.

## Contributions

We welcome contributions to improve this project. If you encounter any bugs or have ideas for enhancements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
