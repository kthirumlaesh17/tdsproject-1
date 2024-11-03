- Data was scraped from the GitHub API by filtering users in Basel with over 10 followers and fetching their most recent repositories.
- A significant portion of repositories in Basel are written in JavaScript but surprisingly PHP is also seen in many repositories.
- Developers in Basel should focus on collaboration in JavaScript-based and Python-based projects to leverage the local expertise and community.
Project Overview
- This project aims to analyze GitHub users based in Basel who have more than 10 followers. By leveraging the GitHub API, we gather user information and their public repositories to uncover insights into user engagement, repository activity, and the impact of licensing on repository visibility.
GitHub Users and Repositories Analysis
- I used the GitHub API to find users in Basel with over 10 followers. For each user, I fetched their details and up to 500 recent repositories, compiling the results into users.csv and repositories.csv while cleaning and formatting the data accordingly.
- Licensed repositories have a consistent average count for both stargazers and watchers, indicating a potential positive impact of having a license.
- Developers should add licenses to their repositories. Licensed projects tend to attract more stargazers and watchers, indicating that clear usage rights enhance engagement and contribute to a more vibrant community around their work. 
