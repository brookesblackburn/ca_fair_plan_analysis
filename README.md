# California FAIR Plan Analysis

An independent research project examining the California FAIR Plan's exposure and structural damage across three major wildfires Eaton, Palisades, and Mosquito. Built with Python, SQL, and interactive geospatial tools using publicly available data from CalFire.

## Interactive Maps

Explore structure-level damage assessments through interactive Folium/Leaflet maps:

- [Eaton Fire - Structure Damage Map](https://brookesblackburn.github.io/ca_fair_plan_analysis/maps/eaton-map.html)
- [Palisades Fire - Structure Damage Map](https://brookesblackburn.github.io/ca_fair_plan_analysis/maps/palisades-map.html)

## Background

The California FAIR Plan is the state's insurer of last resort, providing basic fire coverage to homeowners unable to obtain policies through the private market. Following the January 2025 Los Angeles wildfires, the FAIR Plan faced unprecedented exposure, an estimated $4 billion in claims from the Palisades and Eaton Fire alone resulting in a $1 billion assessment on the voluntary insurance market. This project investigates the geographic and structural dimensions of that exposure using CalFire's damage inspection data.

## Analysis

- **Structure damage mapping** - interactive visualizations of individual structure damage assessments across fire perimeters
- **FAIR Plan coverage analysis** - examining policy concentration in affected areas
- **Insurance market impact** - exploring the relationship between wildfire risk, insurer withdrawals, and FAIR Plan growth
- **CalFire data exploration** - cleaning, querying, and analyzing publicly available damage inspection datasets
- **Geographic/spatial analysis** - mapping damage patterns using coordinate data and GIS tools

## Tools & Technologies

`Python` · `Pandas` · `GeoPandas` · `Folium` · `Plotly` · `SQL` · `Google Colab` · `Excel`

## Data Sources

- [CalFire Damage Inspection Data (DINS)](https://www.fire.ca.gov/)
- [California FAIR Plan - Key Statistics & Data](https://www.cfpnet.com/key-statistics-data/)
- [CA Department of Insurance - Wildfire & Insurance Data](https://www.insurance.ca.gov/01-consumers/200-wrr/)
- [Assembly Standing Committee on Insurance - March 13, 2024](https://calmatters.digitaldemocracy.org/hearings/257632/)
- [Assembly Standing Committee on Insurance - May 28, 2025](https://calmatters.digitaldemocracy.org/hearings/259341/)

## Repository Structure
```
ca_fair_plan_analysis/
├── maps/
│   ├── eaton-map.html            # Interactive Eaton Fire damage map
│   ├── eaton-map-code            # Source code for Eaton map
│   ├── palisades-map.html        # Interactive Palisades Fire damage map
│   └── palisades-map-code        # Source code for Palisades map
└── README.md
```

## Author

**Brookes Heil Blackburn**
M.S. Applied Mathematics — Cal Poly Pomona
[GitHub](https://github.com/brookesblackburn) · [LinkedIn](https://www.linkedin.com/in/brookesheilblackburn)
