# Job-trend-for-MBA-students
This project provides job market trends for especially MBA students, which offer sa month-over-month snapshot of how the job market trends are shifting, what kinds of skill sets employers are looking for, the hottest or fastest-growing industry, and what types of salaries employers pay for specific jobs.

This project consists of two main parts.

Part I is about web-scrapping from online job posting to get the data we need. As a result, we were able to scrape through both Indeed.com and Glassdoor.com with the keyword “fintech” for jobs and got a total number of 1,662 jobs in the U.S. that were posted from Apr 27 2021 to May 27 2021. The variables included in the final scraped dataset are: job titles, company, location, job summary, salary, and date of posting. 


Part II has two sections.

- For time series analysis:
During the hypothesis stage, we hoped to make effective predictions for future FinTech job markets at least for the next year. However, based on research, the quantity of job posting data is limited by its nature. Specifically, job postings don’t stay online for longer than a month to match companies’ real-time recruiting needs, and they will also be taken down as soon as the position is filled or obsolete. What’s more, salary data are mostly available through predictions by experienced recruiting websites when there’s enough historic records.

- For sentiment analysis:
Twitter is one of the world's largest social network applications; people like to express their opinions on Twitter. Therefore, we used the  tweepy package to scrape the latest 6000 tweets related to FinTech to do our sentiment analysis, which provides insights into people’s attitudes towards FinTech.
