# 📊 Event Sensitivity Score — SEC 8-K Disclosures & Market Reactions

## 🧠 Why This Matters
SEC 8-K filings contain critical information about corporate events — from leadership changes to lawsuits.  
This project explores whether *different event types* trigger different market reactions, using NLP-labeled filings and historical stock data.

By quantifying how stock prices respond to each category, we take a first step toward building smarter, event-driven tools for analysts, investors, and trading systems.



## 📁 What’s Inside
- **Preprocessing**: Flattened multi-label 8-K data (up to 3 categories per filing)
- **Return Calculation**: 1-day and 3-day returns computed for each event
- **Visualization**: Bar charts comparing market reaction by category
- **Interpretation**: Written summary of what we observed — and what comes next


## 🔍 Key Observations

- **Litigation and Lawsuit** filings tend to trigger **negative returns**
- Events like **Operational Activities** and **Document Updates** show **modest positive reactions**
- While returns are small, consistent trends emerge — particularly in the 3-day window


## Next Steps

This analysis validates that **text classification can surface financially meaningful signals**.  
I’m currently extending this into:

- **Portfolio-level and strategy-based backtesting**, using event categories to guide risk-aware trades  
- **Forecasting next events** from sequences of SEC filings (sequence modeling)  
- Exploring **sentiment and filing tone** to layer onto event types  


## 👩🏽‍💻 About Me

Built by **Fathmat** — aspiring quant and NLP explorer.  
I’m passionate about building tools that make financial information more actionable.

📫 [Connect on LinkedIn](www.linkedin.com/in/fathmat-bakayoko-30715024a)
