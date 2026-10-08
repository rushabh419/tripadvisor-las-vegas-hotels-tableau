### 1. Project Title
* Title: TripAdvisor Las Vegas Hotels Analytics & Performance Dashboard
* Repository Name: tripadvisor-las-vegas-hotels-tableau

### 2. Short Description
* An exploratory hospitality analytics project developed in Tableau examining customer reviews, hotel star ratings, amenities, and guest demographics for 21 major hotels in Las Vegas.
* Consolidates review ratings, traveler types, stay seasonality, and hotel capacities into an interactive dashboard styled in TripAdvisor's signature green brand theme.

### 3. Purpose
* Evaluate Hotel Service Standards: Assess how star ratings and core amenities (free Wi-Fi, fitness centers, pools, clubs, basketball courts) correlate with guest review scores.
* Profile Visitor Demographics & Behavior: Identify dominant traveler segments (couples, families, business, solo) and visitor geographical origins across continents.
* Analyze Travel Seasonality: Track booking periods and stay duration cycles to determine when demand peaks throughout the year.
* Build Visual Tableau Competencies: Demonstrate proficiency in constructing advanced multi-visual dashboards incorporating highlight tables, tree maps, packed bubble charts, and brand-consistent design styling.

### 4. Tech Stack
* Business Intelligence & Visualization: Tableau Desktop / Tableau Public
* Data Modeling & Calculations: Tableau Calculated Fields, Distinct Counts, Aggregations
* Data Storage / Source: CSV / Flat File

### 5. Example Walkthrough
* Use Case: Analyzing guest composition and amenity impact on top Las Vegas hotels.
* Action: Examine the traveler type tree map alongside the additional services highlight table.
* Observed Insight: Couples constitute the largest customer segment, followed by families, while essential amenities like free Wi-Fi and exercise rooms are ubiquitous; highly differentiated amenities like basketball courts are rarely offered across properties.
* Conclusion: Directs resort marketing teams to tailor promotional packages toward couples and leisure travelers rather than solo guests.

### 6. Data Source
* Dataset: TripAdvisor Las Vegas Hotels Dataset (UCI Machine Learning Repository / GitHub)
* Format: .csv (504 rows, 20 columns covering 21 Las Vegas Strip hotels)
* Key Attributes:
  * User country & User continent: Origin demographics of the reviewer
  * Number of reviews & Number of hotel reviews: Total lifetime reviews submitted by the user
  * Helpful votes: Community engagement score for the review
  * Score: Review rating assigned to the hotel (1 to 5 scale)
  * Period of stay: Season or quarter of the guest visit (e.g., Dec-Feb, Mar-May)
  * Travel type: Segment profile (Couples, Families, Friends, Business, Solo)
  * Amenities (Binary Yes/No): Swimming pool, Exercise room, Basketball court, Club, Free Wi-Fi
  * Hotel name: Name of the hotel property
  * Hotel stars: Official star rating (3 to 5 stars)
  * Number of rooms: Total room inventory capacity of the property
  * Review month & Review weekday: Temporal metadata of review submission

### 7. Features & Highlights
* Summary KPI Scorecards: High-level metric cards displaying Total Hotels (21), Average Room Inventory, Overall Average Review Score, and User Average Review Count.
* Amenities Highlight Table: Color-coded matrix visual mapping amenity availability (free Wi-Fi, exercise room, club, basketball court) across properties.
* Star Rating Distribution Bar Chart: Horizontal bar visual categorizing hotel counts across star classes (3-star, 4-star, 5-star).
* Continental Origin Bar Chart: Ranked visual quantifying user review distribution across visitor continents.
* Seasonality Packed Bubble Chart: Packed bubble chart illustrating traveler volume distribution across distinct stay periods.
* Traveler Type Tree Map: Proportional nested tree map segmenting visitor types (Couples, Families, Friends, Business, Solo).
* Top 10 Hotels by Room Capacity: Ranked highlight table listing the 10 largest hotels by room count.
* TripAdvisor Branded UI: Consistent visual theme utilizing TripAdvisor brand green (#00AF87), high-contrast black cards, and custom-styled layout containers.

### 8. Business Impact & Insights
* Couples Drive the Hospitality Market: Couples make up the largest share of visitors to Las Vegas strip resorts, followed by families and friend groups, indicating package promotions should prioritize leisure entertainment and dining perks.
* Amenity Saturation vs. Differentiators: Standard amenities like Wi-Fi and fitness centers are market table stakes; specialized wellness, entertainment, and nightlife amenities offer greater opportunities for brand differentiation.
* Global Visitor Footprint: Strong representation from North American and European travelers underscores the necessity for targeted international seasonal marketing ahead of major travel months.
* Strategic Recommendations:
  * Hotels with lower room counts should target boutique and experiential couple getaways rather than competing directly on volume with mega-resorts.
  * Align staffing levels and promotional pricing with peak period-of-stay influxes identified in the review seasonality bubbles.
 
### 9.	Screenshots / Demos
Show what the dashboard looks like.
Example: ![Dashboard Preview](https://github.com/rushabh419/tripadvisor-las-vegas-hotels-tableau/blob/main/Tripadvisor.png)
