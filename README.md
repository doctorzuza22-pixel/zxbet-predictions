# ZXBet Predictions

A worldwide football analysis Android app.

## First build
- Android package: `za.co.zxbet.predictions`
- App name: ZXBet Predictions
- Minimum Android: 6.0 (API 23)
- Automated debug APK build: GitHub Actions workflow `.github/workflows/android-build.yml`

## Product rules
- Worldwide coverage, with South African competitions prioritised.
- Monitor fixtures seven days a week.
- Do not publish a selection below 69% estimated probability.
- Show no pick when evidence or data quality is insufficient.
- Record every prediction, including losses.
- Separate model probability from historical hit rate and betting returns.

## Data integrity
The initial app shell does not contain a live football data provider. It intentionally displays no fabricated fixtures, injuries, suspensions, odds, lineups or predictions. A suitable licensed data provider and a calibrated prediction model must be connected before live picks are published.

## Build
GitHub Actions builds a debug APK on every push to `main` and on manual dispatch. Download the artifact named `ZXBet-Predictions-APK` from the successful workflow run.
