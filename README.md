- Data was scraped from the GitHub API by filtering users in Toronto with over 100 followers and fetching their most recent repositories.
- The most surprising insight is that longer bios significantly correlate with more followers, showing that a well-crafted bio can notably boost a user's following—even more so than creating additional repositories.
- To attract more followers, developers should invest in a detailed, engaging bio and focus on quality over quantity in repositories, as these factors more effectively boost influence than simply increasing repo count.



# GitHub Users in Toronto

This repository contains data about GitHub users in Toronto with over 100 followers and their repositories.

## Files

1. `users.csv`: Contains information about 693 GitHub users in Delhi with over 100 followers
2. `repositories.csv`: Contains information about 55786 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 100+ followers
- Up to 500 most recently pushed repositories per user
