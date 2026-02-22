# Paper Trader

A single-page stock trading simulation using paper rules and finite card-deck market model.
Built with vanilla JavaScript and no backend. All state is stored locally.

## Concept

- start with fixed cash
- each day, draw a market event card
- prices change based on deterministic deck rules
- buy/sell whole shares (flat trade fee)
- after N days, evaluate portfolio performance

The deck is finite and shuffled, creating visible probability and replayable strategy.

## Tech Stack

- HTML
- CSS
- vanilla JS (ES Module)
- LocalStorage
- No external dependencies

## MVP Features

- finite shuffled event deck
- multi-ticker price updates
- buy/sell with validation + trade fee
- portfolio value + P&L tracking
- reset + export/import save
