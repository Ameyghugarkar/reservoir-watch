# Reservoir Watch

AI-powered reservoir water-level & drought early-warning system for Pune's drinking-water reservoirs.

## Data contract

reservoir_data.csv columns:
  reservoir_name, date, surface_area_sqkm, cloud_cover_pct

risk_analysis.csv columns:
  reservoir_name, date, surface_area_sqkm, depletion_rate_pct_per_week, risk_level, days_remaining_estimate

  ## Team Roles

- ** Amey — Satellite Data & NDWI Engineer**
  Owns: Google Earth Engine pipeline, NDWI computation, `reservoir_data.csv`

- ** Akshay — Risk Logic & Analysis Engineer**
  Owns: Depletion rate calculation, risk classification, `risk_analysis.csv`

- ** kishan — Dashboard & Presentation Lead**
  Owns: Streamlit dashboard, visualizations, pitch deck
