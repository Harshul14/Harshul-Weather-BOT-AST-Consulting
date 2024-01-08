# NestJS Telegram Weather Bot

This project leverages the NestJS framework and Node.js to create a Telegram bot that provides weather updates to users. It includes functionalities for user subscriptions, an admin panel with Google login for managing settings and user accounts, and utilizes MongoDB to store user data. Integration with the OpenWeatherMap API is employed to fetch weather data.

## Features

- **User Subscription**: Users can subscribe to receive daily weather updates.
- **Periodic Updates**: Weather updates are sent periodically to subscribed users based on their preferences.
- **Unsubscribe Option**: Users can unsubscribe at any time to stop receiving weather updates.
- **MongoDB Integration**: Utilizes MongoDB to store user subscription data securely.
- **Admin Panel**: Includes an admin panel accessible through Google login to manage bot settings (API keys, etc.) and user accounts (blocking, deleting, etc.).
- **OpenWeatherMap API**: Integration with the OpenWeatherMap API to fetch accurate weather data.

## Setup

### Installation

1. Clone this repository.
2. Install dependencies using `npm install` in admin-panel and backend-bot.

### Configuration

1. Obtain API keys from OpenWeatherMap.
2. Configure environment variables (create a `.env` file):
   ```
   TELEGRAM_BOT_TOKEN=enter your telegram bot token
   WEATHER_API_KEY=enter the openweathermap api key
   CITY=DELHI
   DATABASE_CONNECTION_STRING=enter the mongodb connection string
   ```
   
### Running the Application

Run the application in development mode:

```bash
npm run start:dev
```

For production deployment, consider appropriate environment settings and use:

```bash
npm run start:prod
```

### Usage

1. Access the admin panel through the specified URL after starting the application.
2. Users can subscribe to weather updates via Telegram by interacting with the bot.
3. Admins can modify bot settings, manage user accounts, and ensure smooth operation.

## Contributors

- Harshul Varshney(https://github.com/Harshul14)

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to modify this README to fit your project's specifics and add additional sections like troubleshooting, deployment instructions, or any other relevant information!
