# ✈️ Flights Data EDA (Python, Matplotlib & Seaborn)

## Project Overview  
This project explores flight data through **Exploratory Data Analysis (EDA)** to uncover insights about:  
- Airline frequency and popularity  
- Distribution of flight classes (Economy vs Business)  
- Ticket price variations across airlines, classes, and timings  
- Impact of number of stops on flight prices  

The analysis was performed in Python using **pandas, matplotlib, seaborn**, and visualization techniques.  

---

## Dataset  
The dataset contains details about:  
- **Airlines** (Vistara, Indigo, Air India, etc.)  
- **Flight Classes** (Economy, Business)  
- **Ticket Prices**  
- **Departure & Arrival Times**  
- **Number of Stops**  

---

## Key Insights  

- **Most flown airline**: Vistara  
- **Flight timings**: Morning is the most frequent departure time, followed by Early Morning and Evening  
- **Class distribution**:  
  - Only Air India & Vistara offer Business class  
  - Economy dominates (~69% of flights), but Business class generates ~78% of total revenue  
- **Price analysis**:  
  - Business class has significantly higher median and wider price spread than Economy  
  - Vistara & Air India have higher prices (due to Business class), while Indigo, SpiceJet, AirAsia, and GO FIRST stay in lower ranges  
- **Stops vs Price**:  
  - 1-stop flights are the most expensive  
  - Non-stop flights are cheapest  
- **Timing vs Price**:  
  - Night departures & Evening arrivals are pricier  
  - Late-night departures/arrivals are cheapest  

---

## 📈 Visualizations  
The notebook includes:  
- Pivot tables (flight frequency by airline & time)  
- Pie charts (class distribution & revenue split)  
- Box plots (price distribution by class, airline, time, stops)  
- Bar plots (average price by stops)  

---

## ⚙️ How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/abhinandannath13/flights-data-eda.git
   cd flights-data-eda
