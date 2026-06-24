# AFL Coach Career - Changelog

## v6.1.0 - 2026-06-24

### Auto-Arrange Lineup

**New Features:**
- **Auto-Arrange Button** — New "⚡ Auto-Arrange" button on the season screen that instantly optimizes your lineup.

- **Smart Optimization** — One click does what would take minutes manually:
  - Puts your highest-rated players in each position on the field
  - Moves lower-rated players to the bench
  - Ensures natural position compatibility (FBs play FB, MIDs play MID, etc.)
  - No more wasting a 95-rated mid on the bench while an 85 plays

- **Notification Feedback** — Shows "Lineup optimized!" confirmation when complete.

**How It Works:**
1. Click "⚡ Auto-Arrange" on the season screen
2. The game sorts players by natural position and rating
3. Best players fill field spots, rest go to bench
4. Your team rating may improve as position penalties are eliminated

---

## v6.0.0 - 2026-06-22

### In-Season Trading System

**New Features:**
- **Trade Button** — New "🔄 Trade Players" button on the season screen allows you to make trades before playing the season.

- **Trade Modal** — Full trade interface with:
  - Your Players column (sorted by rating) on the left
  - Available Players column (15-20 legends in the trade pool) on the right
  - Click a player from each side to select a trade

- **Trade Evaluation** — Trades are evaluated based on player value (rating + age):
  - 🟢 "Great trade!" — You're getting the better player (+5 value or more)
  - 🟡 "Fair trade" — Both sides benefit roughly equally (-3 to +5 value)
  - 🔴 "Giving up too much" — You're losing value (-4 or worse)
  
- **Limited Trades** — 2 trades per season to prevent roster churning. Counter displayed on season screen.

- **Trade Pool Persistence** — Trade pool saves with your game. Players you trade away become available for future trades.

- **Mid-Season Stats** — Traded-in players get their season stats initialized so they contribute to season leaders.

**How It Works:**
1. Click "🔄 Trade Players" on the season screen
2. Select a player from your roster to trade away
3. Select a player from the available pool to acquire
4. Review the trade evaluation
5. Click "Confirm Trade" to execute
6. New player takes the position of the traded player

---

## v5.0.0 - 2026-06-21

### Player Aging & Retirement System

**New Features:**
- **Player Ages** — Every player now has an age displayed on their card. Ages are assigned based on era:
  - 2020s players: 20-28 years old
  - 2010s players: 26-32 years old
  - 2000s players: 28-36 years old
  - 1990s players: 30-38 years old
  - 1980s legends: 32-40 years old

- **Age-Based Decline** — Players age each off-season and may decline:
  - Players under 30 maintain their rating
  - At 30+, 30% chance of -1 rating per year
  - At 33+, 60% chance of -1 to -2 rating decline
  - At 35+, decline can be -1 to -3 rating
  - Minimum rating is 70

- **Retirement System** — Veterans may retire during the off-season:
  - No retirement before age 32
  - 10% base chance at 32, increasing 10% each year
  - +15% extra chance if rating drops below 80
  - Players 38+ always retire
  - Retired players are automatically replaced with new recruits

- **Visual Age Indicators**:
  - Normal text: Under 31
  - Orange text: Veterans (31-33)
  - Red text: Old guard (34+)

- **Retirement Notifications** — Off-season screen now shows which players retired and their final stats

- **Dynasty Building** — Forces you to continually refresh your roster, making long careers more challenging and rewarding

---

## v4.0.0 - 2026-06-18

### Season Stats Leaders

**New Features:**
- **Player Stats Tracking** — Every player now accumulates stats across the season: disposals, goals, and Best on Ground (BOG) awards.

- **Season Leaders Display** — At the end of each season, see your top performers:
  - 🏃 Most Disposals — Total disposals across all games
  - ⚽ Leading Goalkicker — Most goals kicked
  - ⭐ Best & Fairest — Most BOG awards (determined by weighted performance each match)
  - 📊 Avg Disposals — Highest per-game disposal average

- **Improved BOG Selection** — Best on Ground is now determined by weighted stats (disposals × 1.5 + goals × 3) rather than random selection.

- **Match Display Enhancement** — BOG display now shows goals alongside disposals when the player kicked goals.

- **Position-Based Stats** — Forwards (FF/HF) generate more goals while mids generate more disposals, reflecting realistic AFL stat distribution.

---

## v3.0.0 - 2026-06-11

### Position Management & Team Preview

**New Features:**
- **Player Swapping** — Click any player on the season screen, then click another to swap their positions. Rearrange your team for optimal performance.

- **Position Display** — Each player card now shows their natural position (FB, HB, MID, RUC, HF, FF) so you know where they belong.

- **Out-of-Position Penalties** — Players get a -5 rating penalty when playing outside their compatible positions:
  - FB can play: FB, HB
  - HB can play: HB, FB, MID
  - MID can play: MID, HB, HF
  - RUC can play: RUC, FF
  - HF can play: HF, FF, MID
  - FF can play: FF, HF

- **Coaching Offer Previews** — When you get a coaching offer, click to see the full team roster before deciding:
  - View the entire team on a football field
  - See each player's rating with any position penalties
  - Accept or decline each offer individually
  - Close preview to compare other offers

---

## v2.0.0 - 2026-06-11

### Major Update: Historical Legends & Football Field UI

**New Features:**
- **150 Real AFL Legends** from 1980s to present day
  - Brownlow Medal winners: Leigh Matthews, Gary Ablett Sr/Jr, Dustin Martin, Patrick Cripps, Nick Daicos
  - Coleman Medal winners: Tony Lockett, Jason Dunstall, Lance Franklin, Charlie Curnow
  - Hall of Fame inductees and modern stars
  - Each player has era tag (1980s/1990s/2000s/2010s/2020s)
  - Ratings based on real career achievements (95-99 for multiple Brownlows, etc.)

- **Football Field UI**
  - Visual field layout with position lines (FB, HB, MID, RUC, HF, FF)
  - Interchange bench at bottom
  - Players shown in their actual positions
  - Color-coded ratings (Gold = Elite 94+, Teal = Star 88+, Grey = Good)

- **Improved Recruiting**
  - Off-season recruits shown as cards with full details (name, position, era, original team)
  - Click recruit → click field player to swap
  - Visual feedback during swap process

**Player Pool Highlights:**
- **Defenders:** Stephen Silvagni, Matthew Scarlett, Luke Hodge, Sam Mitchell, Corey Enright
- **Midfielders:** Gary Ablett Sr/Jr, Dustin Martin, Marcus Bontempelli, Patrick Cripps, Nick Daicos, Chris Judd, James Hird
- **Ruckmen:** Dean Cox, Max Gawn, Nic Naitanui, Brodie Grundy, Aaron Sandilands
- **Forwards:** Tony Lockett, Jason Dunstall, Lance Franklin, Charlie Curnow, Wayne Carey

---

## v1.0.0 - 2026-06-11

### Initial Release
- 18 AFL teams to choose from
- 22-player roster with random ratings
- Season simulation with Premier through Bottom 8 results
- Off-season recruiting (5 offered players)
- Coaching offers after successful seasons
- 20-season career with final stats
- Player aging and development system
