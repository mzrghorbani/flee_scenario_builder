# Location and Conflict Data Processing

This repository contains code for extracting and visualizing conflict-related information based on real-world data. The process involves the following key steps:

1. **Location Data Preparation:**
   - Create a directory for the country of interest.
   - Prepare a `population.csv` file containing population data for reference.

2. **Acquiring Conflict Data:**
   - Obtain conflict data in ACLED format.
   - Extract relevant columns to create a DataFrame.

3. **Data Processing:**
   - Format event dates and calculate conflict dates.
   - Filter out events with low fatalities.
   - Sort and remove duplicates from the DataFrame.

4. **Location Classification:**
   - Split data into "towns" and "conflict zones" based on a threshold.
   - Assign a location type to each subset.

5. **Population Assignment:**
   - Create a population dictionary for mapping.
   - Assign population values to the DataFrame.

6. **CSV Output:**
   - Save the final DataFrame to a `locations.csv` file.

7. **Extracting and Visualising Conflicts:**
   - Extract conflict zone data to create a `conflicts.csv` file.
   - Simulate conflict intensity data for visualisation.

8. **Creating Routes:**
   - Routes constructions without Google API.
   - Route constructions using Google API.

This process offers valuable insights into conflict dynamics within the specified country, enabling data-driven analysis and visualisation.

