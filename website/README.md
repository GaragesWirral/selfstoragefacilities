# Self Storage Directory Website

This is a directory website for self storage facilities in the UK, designed to help users find storage facilities near them.

## Project Structure

The website follows this URL structure pattern:
```
domain.com/Region/city/
```

For example:
```
domain.com/Bedfordshire/Kempston/
```

## Features

1. **Homepage**: Optimized for "Self Storage Near Me" searches with:
   - Hero section highlighting the main search functionality
   - Popular regions with the most storage facilities
   - Key benefits of self storage

2. **Regions Page**: Lists all regions with storage facilities, including:
   - Number of cities per region
   - Total facilities per region
   - Search functionality to filter regions

3. **Region Pages**: For each region (e.g., Bedfordshire):
   - Lists all cities in that region with storage facilities
   - Shows the number of facilities per city
   - Search functionality to filter cities

4. **City Pages**: For each city (e.g., Kempston):
   - Lists all storage facilities in that city
   - Displays contact information, location, and website links
   - Optimized for "Self Storage in [City]" searches

## SEO Optimizations

This website includes several SEO optimizations:
- Clean URL structure reflecting geographic hierarchy
- Meta descriptions targeting relevant keywords
- H1 headings optimized for local search terms
- Semantic HTML structure 
- Mobile-responsive design
- Internal linking between related pages

## How to Deploy

1. Upload the entire `website` directory to your web hosting service
2. Ensure your domain points to the website directory
3. No database setup is required as all data is static HTML
4. Test the site to make sure all links work correctly

## Maintenance

To update the website with new storage facilities:
1. Update the Excel file with new data
2. Run the `create_storage_directory.py` script again
3. Upload the updated files to your web server

## Statistics

- Total regions: 79
- Total cities: 1,261
- Total storage facilities: 2,956 