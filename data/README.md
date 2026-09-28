# Data

The raw data is **not stored in this repository** because the files are large and publicly available.

## How to get it

1. Go to [Inside Airbnb – Get the Data](https://insideairbnb.com/get-the-data/)
2. Find **Toronto, Ontario, Canada** and download these four files:
   - `listings.csv.gz` (detailed listings) → unzip to `listings.csv`
   - `calendar.csv.gz` (daily availability) → keep as `calendar.csv.gz`
   - `reviews.csv.gz` (reviews) → unzip to `reviews.csv`
   - `neighbourhoods.geojson` (neighbourhood boundaries)
3. Place all four files in this `data/` folder, then run the notebook in `notebooks/`.

This analysis used the **May–June 2026** snapshot (15,869 listings, 8.11 million calendar rows). Newer snapshots may give slightly different numbers.

## Licensing rules

City of Toronto, Municipal Code Chapter 547 (Licensing and Registration of Short-Term Rentals).
