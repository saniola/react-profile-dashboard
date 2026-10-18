# React Profile Dashboard

A React application rendering a user profile card, a friend list, and a transaction history, built with composable components and static JSON data.

## Components

- **Profile** — displays username, tag, location, avatar, and stats (followers, views, likes).
- **FriendList** — renders a list of friends with online status, using `FriendListItem` for each entry.
- **TransactionHistory** — renders a table of transactions (type, amount, currency).

## Stack

- React 18
- Vite
- Sass (CSS Modules)
- ESLint

## Usage

```bash
npm install
npm run dev
```

Other scripts:

```bash
npm run build     # production build
npm run preview   # preview the production build
npm run lint      # run ESLint
```
