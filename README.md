# Exploring LGBTQ+ Online Visibility: News Volume and Google Search Interest

This project forms part of the Codecademy Analyse R Skill Path and is the final capstone project required to complete the course.

In this project, I analyses patterns in UK-based Google search interest and online news coverage related to LGBTQ+ and transgender topics between November 2020 and November 2025.

Using **Google Trends** data (via the `gtrendsR` package) and **GDELT** news data, the project explores how public search behaviour relates to media attention over time, with a focus on seasonality, temporal dynamics, and short- versus medium-term impacts on media coverage.

## Research questions
- How does relative Google search interest (RSI) for LGBTQ+ and transgender-related search terms vary over time in the UK?
- To what extent do changes in news media volume and tone align with search interest?
- Are there short-term or delayed temporal relationships between media coverage and search behaviour?

## Data Sources
- **Google Trends**: Weekly relative search interest for selected search terms extracted via the `gtrendsR` package. 
- **GDELT 2.1**: Daily news article volume and tone, aggregated to weekly resolution, extracted via GDELT API.

## Methods
- Descriptive and seasonal analysis
- Correlation and cross-correlation analysis
- Linear regression
- Distributed lag modelling (DLMs)
- Newey–West standard errors to account for autocorrelation.

## Key findings
- Search interest for both topics responds primarily to contemporaneous media coverage.
- Media coverage exhibits strong short-term persistence for both topics.
- Transgender-related coverage shows additional medium-term structure, suggesting more sustained and complex patterns of media attention than LGBT+ coverage.
- These dynamics are consistent with event-driven public interest shaped by political, legislative, and journalistic cycles.

## Outputs
- A fully reproducible R Markdown report (HTML)
- Cleaned and aggregated datasets
- Analysis code suitable for portfolio and further development

## Notes
Google Trends data are based on **search terms rather than Google-defined Topics**, due to limitations in reliably querying Knowledge Graph topic identifiers via the `gtrendsR` interface. All analyses focus on temporal dynamics within terms rather than absolute comparisons across topics.

## Author
Bek Rengel
