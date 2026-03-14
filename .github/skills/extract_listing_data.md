---
name: extract_listing_data
description: Extract and normalize structured data from a used-car listing
---

# Purpose
Transform raw ad content into normalized vehicle data.

# Extract Fields
- make
- model
- trim
- year
- horsepower
- fuel
- transmission
- mileage
- price
- location
- seller_type
- source
- url

# Normalization Rules
- Mileage numeric in km
- Price numeric in euros
- Horsepower in ch

# Missing Data
If unavailable use:
not specified