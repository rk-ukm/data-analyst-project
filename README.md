IBM Project </br>
Done in Google Looker Studio. </br>

## Project Summary

The survey highlights who the respondents are (age, country, educaation) and what technologies they use today vs. what they want to adopt in the future.
We have 3 major trends, adaptations and current streams to deal with:
Current Usage: Today’s stack is dominated by JavaScript, SQL, HTML/CSS, with PostgreSQL, MySQL, and SQLite as top databases. AWS, Azure, Google Cloud lead the platforms, and React, Node.js dominate frameworks.

Future Trends: Respondents show strong desire for TypeScript, Rust, Go (languages with growth potential). PostgreSQL and MongoDB remain highly desired. Cloud continues to dominate (AWS, Azure, Google Cloud). Framework adoption is moving toward Next.js, React, and Vue.js.

Demographics: Majority of respondents are aged 25–34, heavily represented in countries like the US, with most holding a Bachelor’s degree.
Key insight: There’s a gap between current usage and future interest—emerging technologies (e.g., Rust, Next.js) show much higher desire compared to current penetration.


### Major Key Points

Context: The survey captures the global developer landscape across demographics, skills, and preferences.
Purpose: To compare current technology usage with future aspirations, helping stakeholders identify adoption trends, training needs, and market opportunities.
Scope: Three dashboards:
Demographics (who the respondents are)
Current Usage (what technologies are used today)
Future Trends (what technologies developers want to work with next year)


### Key Methodologies Found and Utilised

Data Source: Survey dataset (survey_data_updated.csv).
Processing:
Multi-select fields (languages, databases, platforms, frameworks) split and normalized in BigQuery.
Nulls cleaned, coding years converted to numeric, and “Top 10” pre-aggregated for clarity.
Visualization:
Built in Google Looker Studio.
Demographics: Pie, Map, Bar + Line, Stacked Bar.
Usage/Trends: Bar, Column, Word Cloud/Treemap, Bubble Charts.
Metrics: Primarily Record Count (number of respondents mentioning each technology), with derived percentages for distribution clarity.


--> To find in details please view the .pdf report </br>
Many Thanks
