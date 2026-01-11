# Customer Support Tickets Sentiment Analysis

## Project Overview
This project analyzes customer support tickets using sentiment analysis to understand customer satisfaction and identify problem areas.

## Dataset
- **Source**: [Customer Support Tickets Dataset on Kaggle](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset)
- **Total Tickets**: 8,469 customer support tickets
- **Description**: Dataset contains customer support tickets with information about products, customer details, ticket descriptions, and resolution data.

## Key Findings
- **52.0%** of tickets express positive sentiment
- **28.9%** of tickets show negative sentiment  
- **19.1%** of tickets are neutral
- Top products with complaints: Roomba Robot Vacuum, Canon EOS, Canon DSLR Camera

## Technologies Used
- Python 3
- pandas - Data manipulation
- numpy - Numerical operations
- matplotlib - Data visualization
- TextBlob - Sentiment analysis

## Project Structure
```
customer_support_project/
├── data/
│   └── customer_support_tickets.csv
├── notebooks/
│   └── ticket_analysis.ipynb
├── results/
│   ├── analysis_summary.txt
│   ├── sentiment_bar_chart.png
│   ├── sentiment_pie_chart.png
│   └── top_negative_products.png
└── README.md
```

## How to Run
1. Install required libraries: `pip install pandas numpy matplotlib textblob`
2. Open `notebooks/ticket_analysis.ipynb` in Jupyter
3. Run all cells

## Results
The analysis reveals that despite being support tickets, over half express positive sentiment, suggesting customers remain polite even when reporting issues. Key problem products have been identified for business action.

## Author
[Muftau Mahmud]

## License
MIT License