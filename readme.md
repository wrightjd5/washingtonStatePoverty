# Washington Poverty and Discount Stores Map

An interactive map showcasing poverty data for Washington counties along with the locations of discount and charity stores.

## Table of Contents
- [About](#about)
- [Map Preview](#map-preview)
- [How to Use](#how-to-use)
- [Data Sources](#data-sources)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

This interactive map visualizes the number of people in poverty per county in Washington, overlaying the distribution of discount and charity stores. The map provides a comprehensive view of poverty statistics and store locations to aid in understanding the socio-economic landscape.

## Map Preview

Include a screenshot or GIF showcasing your map. You can also provide a link to an online demo if available.

## How to Use

1. **Hover over a County:** Move your cursor over a county to view the number of people in poverty.

2. **Click on a County:** Click on a county to zoom in and explore more detailed information.

3. **Discount and Charity Stores:** Icons on the map represent the locations of different types of stores. Click on the icons to view store names.

## Data Converstion Process

Shapefile representing counties in Washington State was found on IGISMap and then converted to geoJson using geojson.com. Data representing the number of people 0-17 in poverty per county in Washington was found from the U.S. Department of Agriculture - Economic Research Service and was joined the the Washington counties geojson file using geojson.com. The point data representing the number of discount and charity stores was found as a shapefile on IGISMap and was then converted to geojson format using geojson.com

## Data Sources

- **Poverty Data:** [U.S. Department of Agriculture]
- **Store Locations:** [i GisMaps]

Include any necessary attribution or credits for the data sources.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a pull request

## Contact

For any inquiries or feedback, please contact [Jason Wright] at [wrightjd5@appstate.edu].
