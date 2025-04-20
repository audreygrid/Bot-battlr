# Bot Battlr

**Bot Battlr** is a React application that allows users to build and manage their own army of AI bots. Bots are selected from a central collection, each with unique stats and class types. Users can enlist bots, release them, or permanently discharge them from service. The UI follows a clean, futuristic design inspired by modern video game aesthetics.

## Features

- View all available bots in the `BotCollection` component
- View full specs for an individual bot in `BotSpecs`
- Enlist a bot to your army (only one bot per class)
- Release a bot back to the collection
- Discharge a bot to remove it permanently from both frontend and backend
- Sort bots by health, damage, or armor
- Filter bots by one or more classes
- Bot army displayed in `YourBotArmy` component

## Bot Data Structure

Example bot object from `db.json`:

```json
{
  "id": 101,
  "name": "wHz-93",
  "health": 94,
  "damage": 20,
  "armor": 63,
  "bot_class": "Support",
  "catchphrase": "1010010101001101100011000111101",
  "avatar_url": "https://robohash.org/nostrumrepellendustenetur.png?size=300x300&set=set1",
  "created_at": "2018-10-02T19:55:10.800Z",
  "updated_at": "2018-10-02T19:55:10.800Z"
}

Usage
Click a bot card to view detailed stats

Click "Enlist" to add a bot to your army (only one bot per class allowed)

Click a bot in YourBotArmy to release it back to the collection

Click the red "x" button to permanently discharge a bot

Use the filter and sort components to refine the collection view

Styling
Plain CSS only (no CSS frameworks)

Layout and colors are inspired by futuristic, game-like UIs

Responsive design for mobile and desktop

