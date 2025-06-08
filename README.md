
# Employee Sentiment Analysis

 - This project analyzes internal employee messages to label sentiment, monitor engagement, and identify potential flight risks.
 - It analyzes employee messages to evaluate sentiment and engagement.

## 2. Project Objective
   The main goal is to evaluate employee sentiment and engagement by performing the following:
    - Sentiment Labeling: Automatically label each message as Positive, Negative, or Neutral.
    - Exploratory Data Analysis (EDA): Analyze and visualize the data to understand its structure and underlying trends.
    - Employee Score Calculation: Compute a monthly sentiment score for each employee based on their messages.
    - Employee Ranking: Identify and rank employees by their sentiment scores.
    - Flight Risk Identification: A Flight risk is any employee who has sent 4 or more negative mails in a given month.
    - Predictive Modeling: Develop a linear regression model to further analyze sentiment trends.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/username/employee-sentiment-analysis.git

## Summary of Tasks

1. **Sentiment Labeling**: Messages were labeled as Positive, Negative, or Neutral using TextBlob.
2. **EDA**: Visualizations showed sentiment distribution and message frequency over time.
3. **Score Calculation**: Monthly sentiment scores were computed per employee.
4. **Employee Ranking**: Employees ranked by monthly sentiment.
5. **Flight Risk Detection**: Identified employees with 4+ negative messages in any 30-day window.
6. **Predictive Modeling**: A linear regression model was built to forecast sentiment trends.

## Top 3 Positive Employees
- kayne.coulter@enron.com (Score: 5)
- patti.thompson@enron.com (Score: 5)
- eric.bass@enron.com (Score: 4)

## Top 3 Negative Employees
- bobette.riner@ipgdirect.com (Score: 0)
- john.arnold@enron.com (Score: 2)
- johnny.palmer@enron.com (Score: 2)

## Employees Flagged as Flight Risks
- john.arnold@enron.com
- patti.thompson@enron.com
- bobette.riner@ipgdirect.com
- rhonda.denton@enron.com
- johnny.palmer@enron.com
- lydia.delgado@enron.com
- sally.beck@enron.com

## 🔍 Key Insights
- Majority of employee communications were positive in tone.
- Specific employees exhibited consistent negativity across multiple months.
- Repeated negative messages in short time frames helped flag potential flight risks.
- Sentiment trends vary by time period and can serve as early indicators of morale shifts.

## Visuals Included

 - Better understanding of the analysis and trend analysis.
 - Linear model trend for the predictive model is being visualized.

## 💡 Recommendations
- Reach out to at-risk employees for feedback or intervention.
- Celebrate and promote engagement from top performers.
- Incorporate sentiment analytics in ongoing HR review cycles.


