# 🎰 Slot Machine

A simple browser-based slot machine game. Spin the 3 reels, stop them as you like, and try your luck! BET increases the number of valid lines. Bonus/penalty features such as "7", diamond, and skull are included.

## Features

- 3 reels with a variety of symbols
- BET selection (1-3) and MAX BET
- Start spinning with SPIN button, stop manually with STOP buttons
- Number of active lines increases with BET (up to 5 lines)
- Bonus & penalty features
- Play until your credit reaches zero

## How to Play

1. Choose your BET amount using "−", "＋", or "MAX BET" buttons (initial credit: 100).
2. Click "SPIN" to start.
3. Stop each reel at any timing with "STOP Left/Middle/Right".
4. Get credits for matching symbols and bonuses!

## Pay Table & Bonus

| Symbol      | Payout (per BET)  |
|-------------|:-----------------:|
| seven       |       50          |
| bar         |       30          |
| diamond     |       20          |
| bell        |       10          |
| star        |        5          |
| cherry      |        3          |
| skull       |  0 (penalty only) |

### Bonus & Penalty

- 2 "7" on the center row: +10 × BET credits
- 2 diamonds on the center row: next spin is free (no BET deducted)
- 2 or more skulls on the center row: -100 credits

### Line Details

- BET 1: Only center horizontal line active
- BET 2: Top & bottom horizontal lines added (total 3 lines)
- BET 3: Diagonals (／ and ＼) also active (total 5 lines)

## Symbol Images

- Place `seven.png`, `cherry.png`, `bell.png`, `star.png`, `bar.png`, `diamond.png`, and `skull.png` in the `img/` folder.

## Demo

[Slot Machine Demo Page](https://ss872927.stars.ne.jp/slot/)  
*The demo page is in Japanese.*

## License

MIT

## Author

[GratifluxTools](https://github.com/GratifluxTools/slot-machine.git)

---

⭐ Please star this repo if you like it!
