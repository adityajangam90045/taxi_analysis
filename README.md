# taxi_analysis
 
 Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis


 
🔍 Overview

Can payment method influence how much taxi drivers earn?

This project explores fare patterns using 6.4M+ taxi trip records, comparing card and cash payments to understand what actually drives revenue.

🎯 Objective

To compare average fares between card and cash transactions and identify the key factors influencing any observed differences.

❓ Key Question

Is the difference in fare between card and cash payments real — or driven by other factors like trip distance?

📊 What I Did

Cleaned and prepared large-scale taxi trip data (6.4M+ rows)

Removed invalid entries and handled outliers using the IQR method

Compared average fares across payment types

Analysed trip distance patterns

Applied statistical testing to validate whether differences were meaningful


📈 Key Findings
Card payments showed a higher average fare (13.11 vs 11.76)

The difference was statistically significant (p < 0.05)

However, card users travelled longer distances (2.99 vs 2.60 miles)

This explains most of the fare difference


💡 Insight

At first glance, it looked like payment method influenced revenue.

But deeper analysis showed:

👉 Trip distance — not payment type — is the real driver of higher fares

⚠️ Important Learning

A statistically significant result does not always mean causation.

Without deeper analysis, it’s easy to draw misleading conclusions from data.

🛠️ Tools Used
Python


Pandas

NumPy

SciPy

Matplotlib



🚀 Next Steps
Use regression analysis to control for distance and other variables

Explore additional factors (time, location, demand patterns)

Build an interactive dashboard for visual insights
