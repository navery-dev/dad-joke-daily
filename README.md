# Dad Joke of the Day 👨

A simple, fun web page that displays a different dad joke every day. Created as a Christmas present for my dad.

## Features

- **Daily Jokes**: Shows a new dad joke each day from a collection of 150+ jokes
- **Special Holiday Animations**: Falling emojis on special dates including:
  - Valentine's Day 💕
  - Father's Day 👔
  - 4th of July 🇺🇸
  - Thanksgiving 🦃
  - Christmas 🎄
  - New Year's Day 🎊
  - My Dad's Birthday 🎉
- **Responsive Design**: Works great on desktop and mobile devices
- **Auto-Updates**: Automatically refreshes at midnight to show the next day's joke

## How It Works

The page uses a simple algorithm to select a joke based on the number of days since January 1, 2024. This ensures:
- Everyone sees the same joke on the same day
- Jokes cycle through the entire list before repeating
- No random selection means consistency across visits

## Setup

Simply open `index.html` in your web browser. No server or installation required!

You can also host it on GitHub Pages:
1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select your branch and root folder
4. Your site will be live at `https://yourusername.github.io/dad-joke-daily/` (Currently hosted on https://navery-dev.github.io/dad-joke-daily/)

## Customization

Want to personalize it? Here's what you can easily change:

### Add More Jokes
Edit the `dadJokes` array in `index.html` (starting around line 150) and add your own jokes!

### Add Special Dates
In the `checkSpecialDates()` function (around line 218), you can add more special dates with custom messages and emojis.

### Adjust Animation Settings
In the `createFallingEmojis()` function (around line 290):
- Change `emojiCount` to increase/decrease number of falling emojis
- Change `duration` to make the animation last longer/shorter
- Adjust `interval` to control how fast emojis spawn

## Technologies Used

- Pure HTML, CSS, and JavaScript
- No frameworks or dependencies
- Completely self-contained in a single file

## License

Feel free to use this project for your own family and friends!

---

Made with ❤️ for Dad
