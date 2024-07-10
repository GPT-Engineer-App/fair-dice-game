# fair-dice-game

create a dice game site that has the following features 


Sure, here is a summary of the features we currently have:

1. **Provably Fair Dice Game**: 
   - Players can roll a dice.
   - The outcome is determined by a combination of a server-generated seed and player input.
   - The server seed is hashed and shared with the player at the start of the game.
   - The original server seed is revealed after the game ends for verification.

2. **User Balance Management**: 
   - Each user has a balance that updates after each game based on the outcome.
   - Users can select how much they want to wager on each roll.

3. **Winning Chance Selection**: 
   - Users can select their chance of winning for each roll.

4. **Payout Requests**: 
   - Users can request a payout to withdraw their winnings.
   - Payout requests are visible in the admin dashboard for review and processing.

5. **Admin Dashboard**: 
   - View statistics such as the number of users currently online, the total amount wagered in the last 24 hours, and the currently pending payout requests.
   - Numerical count of the number of logged-in users.
   - Graph of profit vs. loss for the day.
   - Amount wagered for the day.
   - Amount of cash-out requests.
   - Counter for the total number of bets placed.
   - Counter for the number of bets placed today.

6. **Wallet UI for Cryptocurrency Deposits**: 
   - Users can generate deposit addresses for BTC, ETH, LTC, Doge, and TRX.
   - Each deposit address is unique to each user.
   - Users can switch between different currencies if they have deposited multiple currencies.
   - The balance changes when a user switches between different cryptocurrencies.

7. **Bet Feed**: 
   - Displays a list of rows with information such as the username, the chance, the amount wagered, the result, and the bet ID.

8. **Roll ID**: 
   - Each game has a roll ID saved against the user to track their historical wagering.

9. **Client Seed Prefill**: 
   - The client seed is prefilled with a random string, allowing the user to optionally change it.

10. **Balance Display in Navbar**: 
    - The user balance is displayed in the navbar.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/fair-dice-game.git
cd fair-dice-game
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
