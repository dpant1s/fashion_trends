**Live App:** [fashiontrendsbydikshyapant.streamlit.app](https://fashiontrendsbydikshyapant.streamlit.app)
# Fashion & Beauty Trend Tracker

A weekly fashion & beauty trend tracker that identifies trending styles 
using Google Trends and fetches real products via SerpAPI Google Shopping.

## Stack
- **Python** — data pipeline
- **pytrends** — Google Trends keyword discovery
- **SerpAPI** — Google Shopping product fetching
- **PostgreSQL (Supabase)** — cloud database
- **Streamlit** — dashboard UI
- **Cron / GitHub Actions** — weekly automation

## How it works
1. pytrends finds trending fashion & beauty keywords each week
2. SerpAPI fetches real products from Google Shopping for those keywords
3. Products and prices are saved to Supabase
4. Streamlit displays them in a live dashboard
