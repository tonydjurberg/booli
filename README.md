# Booli Mäklarscraper

Real Windows GUI scraper for Booli's Swedish agent directory.

- Real GUI application, not a terminal-only program.
- Opens Microsoft Edge or Chrome with a persistent local browser profile.
- Optional Booli email/password fields are entered at runtime only and are not saved to disk.
- Collects individual /maklare/... profile URLs.
- Opens each individual profile and extracts available profile-level data.
- Saves continuously to booli_maklare.csv.
- Resumes using state.json.
- Failed profiles are written to failed_profiles.csv.
- Does not bypass CAPTCHA or security challenges.
- Includes self-tests and a Windows GUI startup smoke test in GitHub Actions.

Output:
%LOCALAPPDATA%\BooliMaklarScraper\export\booli_maklare.csv


Build verification marker: Windows workflow package ZIP enabled.
