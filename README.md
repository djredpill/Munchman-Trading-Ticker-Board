# Paper Desk Terminal

Public paper-only screen for Mr. Munchman's pretend trading desk.

This site is **paper only**. It starts from **$500 of pretend money**. It does not connect to a brokerage, and it cannot place real orders.

The GitHub Pages URL is public. Anyone with the link can open it:

https://djredpill.github.io/Munchman-Trading-Ticker-Board/

`index.html` reads the committed book in `snapshot.json` (about $500 cash and equity, $0 P&L, no open positions, and no closed trades). When the browser can reach a public price feed, the page refreshes displayed BTC, ETH, and SOL quotes. Those quotes are display-only. If the feed is blocked, the page keeps the snapshot prices and their as-of times.
