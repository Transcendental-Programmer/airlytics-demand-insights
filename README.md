# Airline Booking Market Demand Analytics

A modern Python web application that analyzes airline booking market demand trends for Australian routes using real-time data and AI-powered insights.

## 🚀 Features

- **Real-time Data Analysis**: Fetches live airline booking data
- **AI-Powered Insights**: Uses OpenRouter API for intelligent trend analysis  
- **Interactive Dashboard**: Beautiful, responsive web interface
- **Market Intelligence**: Route popularity, pricing trends, demand patterns
- **Filtering & Visualization**: Dynamic charts and tables

## � Quick Setup

### **Local Development:**
1. **Install Dependencies**:
```bash
pip install -r requirements.txt
```

2. **Configure APIs** (Optional):
```bash
cp .env.example .env
# Add your API keys to .env file
```

3. **Run the App**:
```bash
python app.py
```

4. **Open Browser**: Navigate to `http://localhost:5000`

### **🌐 Deploy to Production:**

#### **Render (Recommended - FREE):**
1. Fork this repo on GitHub
2. Connect to [render.com](https://render.com)
3. Create new "Web Service" from GitHub repo
4. Render auto-detects settings from `render.yaml`
5. Deploy! ✨

#### **Heroku:**
1. Install Heroku CLI
2. `heroku create your-app-name`
3. `git push heroku main`
4. `heroku open`

#### **Railway/Vercel:**
- Files included: `Procfile`, `runtime.txt`
- Just connect your GitHub repo and deploy!

**Note**: App binds to `0.0.0.0` and uses `PORT` environment variable for proper deployment.

## 📊 Dashboard Features

- **Route Demand Chart**: Bar chart showing demand percentages by route
- **30-Day Trends**: Line chart displaying booking patterns over time
- **Popular Routes Table**: Sortable table with pricing and demand metrics
- **AI Insights**: Automated analysis of market trends
- **Real-time Filters**: Filter by route and minimum demand threshold

## 🔧 API Integration

### Free APIs Used:
- **OpenSky Network**: **100% FREE** real-time flight data (no registration needed!)
- **OpenRouter**: AI analysis (free models available, optional)

### ✨ No Credit Card Required:
OpenSky Network provides completely free access to live flight tracking data with no API key needed!

## 💡 Key Insights Provided

- Most popular flight routes
- Price volatility analysis  
- Peak demand periods
- Route profitability indicators
- Seasonal booking trends

## 🎯 Business Value

Perfect for:
- **Travel Agencies**: Market demand analysis
- **Airlines**: Route optimization  
- **Hospitels**: Understanding traveler patterns
- **Investors**: Aviation industry insights

## 🏗 Technical Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML5, TailwindCSS, Chart.js
- **APIs**: AviationStack, OpenRouter
- **Data**: Pandas for processing

## 📈 Performance

- Fast loading with optimized API calls
- Responsive design for all devices
- Real-time data updates
- Minimal token usage for AI analysis

---

**Ready to analyze airline market demand? Start the app and explore the insights!** ✈️
