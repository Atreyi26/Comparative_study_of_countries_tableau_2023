# Comparative Study Dashboard

## Problem Statement

Create a dashboard for a comparative study on various parameters of different countries using the sample insurance dataset and the world development indicators dataset. Utilize data blending with relationships between Country Code, Country, and Year.

## Datasets

- **Primary Dataset:** Insurance Sample Dataset
- **Secondary Dataset:** Global Financial Development Database

## Dashboard Description

1. **Geographic Map:**
   - Show countries on a map.
   - Color the map based on the Income column from the secondary dataset.
  
2. **Income Group Filter:**
   - Include a filter for the income group on the dashboard.

3. **Webpage Integration:**
   - Create a webpage to display data from the World Bank webpage.
   - Use URL action triggered by the geography graph. Country names will act as the trigger.
   - Link: [World Bank Webpage](https://data.worldbank.org/country/<country>?view=chart)

4. **KPI Table:**
   - Compare the selected period with the prior period.
   - Include parameters for Year Selection and Category Selection.
   - Categories: Life Insurance Share, Market Share, Penetration, Ratio of Reinsurance Accepted, Retention Ratio.
   - Calculate Growth % using a calculated field.
   - Display values in a table with a title updated based on the category selection.

5. **Growth Indicators:**
   - Create shapes indicating growth percentage.
   - Shapes: Negative, No Change, Positive.
   - Apply shapes against corresponding growth values.

6. **Trend Line:**
   - Show a trend line for selected category values.
   - Include an arrow/triangle at the last mark.

7. **Dashboard Filter:**
   - Apply a dashboard filter for the income group to all charts.
   - Enable filter action in the map.

8. **Formatting:**
   - Format all visualizations appropriately for a cohesive and professional look.

## Usage

1. Load the primary and secondary datasets into your data visualization tool.
2. Connect and blend data based on relationships between Country Code, Country, and Year.
3. Build visualizations as described above.
4. Use provided filters and parameters to explore and analyze data.

## Notes

- Ensure data blending is correctly set up with relationships.
- Check that the URL action is functioning as expected.
- Format the dashboard for a polished and user-friendly appearance.

Feel free to reach out for any further assistance or clarifications.

Happy dashboarding!
