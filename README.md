# O1 Prompt Counter

A minimalist web application designed to help users track and manage AI prompt usage with automatic quota resets. Perfect for keeping track of subscription-based AI services where prompts reset on a schedule.

## Features

- **Prompt Counter**: Simple interface to track remaining prompts
- **Usage Tracking**: One-click prompt usage recording
- **Automatic Reset**: Schedule automatic prompt quota resets
- **Daily Average**: Shows average prompts available per day until reset
- **Persistent Storage**: Uses localStorage to maintain count across browser sessions
- **Responsive Design**: Works on both desktop and mobile devices

## How It Works

1. **Set Your Total**: Input your total prompt allocation
2. **Set Reset Time**: Configure when your prompts should reset
3. **Track Usage**: Click "Use Prompt" whenever you use a prompt
4. **Monitor Average**: View your daily prompt budget based on remaining days

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies
- Uses browser's localStorage for persistence
- Responsive design using modern CSS features
- Automatic quota reset system with customizable schedule

## Usage

Simply open `index.html` in any modern web browser. No server or installation required.

### Setup

1. Enter your total prompt allocation
2. Set your reset date/time (optional)
3. Start tracking your prompt usage

The counter will automatically:
- Persist your count across browser sessions
- Calculate daily prompt averages
- Reset to your total allocation at the specified time

## Browser Support

Works in all modern browsers that support:
- localStorage
- ES6 JavaScript
- Modern CSS features

## Contributing

Feel free to open issues or submit pull requests with improvements.
