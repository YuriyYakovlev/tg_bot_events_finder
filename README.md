# Events Finder Bot

This Telegram bot helps users discover new events by scraping public websites across various themes. Admins can integrate the bot into their groups to receive real-time event announcements, ensuring they stay updated with the latest happenings. The bot is designed to automatically gather event details based on predefined categories and notify the group about upcoming events.

## Introduction
Events Finder Bot was created to simplify the process of finding relevant events for Telegram groups. By scraping public event websites with different thematic categories, the bot provides timely and accurate event announcements. It's ideal for community groups, interest-based clubs, and anyone looking to stay informed about events in their area or specific fields. The project is open-source, allowing others to contribute and enhance its functionality.

## Description
The Events Finder Bot is designed to:
- Automatically scrape and announce new events based on selected themes (e.g., concerts, conferences, meetups).
- Provide easy integration into Telegram groups for real-time event updates.
- Filter events by category to match the interests of different communities and groups.
- Ensure that group admins can customize the bot's notifications for better relevance and convenience.

This bot uses web scraping technology to extract event details from a variety of sources, which are then filtered and formatted for easy sharing within Telegram groups.

## Features
- **Event Scraping**: The bot collects and categorizes event data from public websites.
- **Thematic Event Categories**: Admins can define categories (such as music, tech, or sports) for tailored event announcements.
- **Real-time Notifications**: Provides group admins with instant event updates as soon as new events are detected.
- **Customizable Filters**: Allows group admins to adjust event search criteria based on their group's interests.
- **Seamless Telegram Integration**: Directly posts events to Telegram groups with ease, ensuring timely and convenient communication.

## Technologies
The bot is built with the following technologies:

- **Python**: For web scraping and backend logic.
- **BeautifulSoup**: A library used for parsing and extracting data from event websites.
- **Requests**: For making HTTP requests to fetch event data from external sites.
- **Telegram Bot API**: Facilitates seamless communication and event notifications within Telegram.
- **Cron Jobs**: Ensures periodic event scraping and timely announcements.
- **Docker**: Enables easy deployment in a containerized environment.

## Getting Started
This bot is open-source, and contributions are welcome! To get started with development:

1. **Fork** the repository to your GitHub account.
2. **Clone** your fork to your local environment.
3. **Create a branch** for each new feature or fix.
4. **Develop** your changes with meaningful commit messages.
5. **Submit a pull request** for review and potential inclusion in the main repository.

## Installation
To set up the bot locally:

1. Clone the repository.
2. Install dependencies with `pip install -r requirements.txt`.
3. Set up environment variables for:
   - `TELEGRAM_BOT_TOKEN` (your Telegram bot token)
   - `EVENT_SOURCES` (URLs of the event websites to scrape)
4. Configure the bot for specific event categories and keywords.
5. Start the bot:
   - Run `python bot.py` to begin the event scraping and notifications.

## License
This project is distributed under an open-source license, allowing free use, modification, and distribution. Contributions are encouraged to help improve the bot and expand its capabilities.
