 I used python for scraping the data via requests library and csv library to convert the data to csv format. I first sorted out the users and collected it in a file and then fetched info for users.csv and repositories.csv using the file.
• Noteworthy Trend: The MIT license stands out as the most popular choice, followed by the Apache-2.0 and GPL-3.0 licenses. This pattern highlights a strong preference among developers for permissive or widely-recognized licenses. Interestingly, unlicensed or custom licenses are also common in the dataset. Overall, most licenses have low adoption rates, with around 80% of stargazers and watchers clustering around just four licenses. This indicates limited diversity in license choice for popular repositories.
• Suggestions for Developers: For developers seeking increased visibility and engagement, adopting the MIT, Apache-2.0, or GPL-3.0 licenses could be beneficial, as these tend to attract larger communities. Selecting a well-known permissive license like MIT might encourage broader user adoption, while opting for a license like GPL-3.0 could resonate with developers who prioritize copyleft principles, potentially fostering more substantial contributions.
# GitHub Users in Zurich

This repository contains data about GitHub users in Zurich with over 50 followers and their repositories.

## Files

1. `users.csv`: Contains information about 474 GitHub users in Delhi with over 50 followers
2. `repositories.csv`: Contains information about 29036 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-31
- Only included users with 50+ followers
- Up to 500 most recently pushed repositories per user
