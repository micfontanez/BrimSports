# BrimSports

BrimSports is a personal, mobile-first sports dashboard built as an installable Progressive Web App (PWA).

## Favorite teams

- Chicago Bears
- Chicago Blackhawks
- Chicago Cubs
- Chicago White Sox
- Tottenham Hotspur
- Michigan Wolverines football

## Current release: V4

BrimSports V4 includes:

- Today dashboard for favorite teams plus featured neutral games
- Live, final, and upcoming game states
- Team pages with schedules, recent results, and standings
- Sports Day one-day planner and seven-day agenda
- BrimSports Watch Score for featured neutral games
- Game-detail sheets with TV, venue, share/calendar information
- Score-hiding/spoiler mode
- Central Time display
- Local last-known sports-data cache
- Installable PWA shell and offline app assets

## Data

BrimSports currently uses public-facing ESPN JSON endpoints. They are unofficial feeds, so the data layer is kept separate from the presentation layer so a different sports-data provider can be swapped in later.

## Hosting

The repository includes a GitHub Pages deployment workflow under `.github/workflows/deploy-pages.yml`.
