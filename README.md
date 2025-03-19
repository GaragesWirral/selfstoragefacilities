# Self Storage Finder

A comprehensive directory website for self-storage facilities in the UK. This project provides a user-friendly interface for finding storage facilities by region and city.

## Features

- Browse storage facilities by region and city
- Search functionality to quickly find specific locations
- Detailed information about each storage facility
- Mobile-responsive design
- FAQ section with commonly asked questions about self storage
- Comprehensive navigation system
- Legal pages including Privacy Policy, Terms and Conditions, and Membership Terms

## Technology

- Built with HTML, CSS, and JavaScript
- No external libraries or frameworks required
- Simple and lightweight design for fast loading

## Structure

- `index.html` - Homepage with search functionality and featured regions
- `regions.html` - Listing of all regions with search capability
- Region pages - Individual pages for each region listing all cities
- City pages - Individual pages for each city listing all storage facilities
- `assets/` - Directory containing CSS and JavaScript files
- `assets/css/style.css` - Main stylesheet
- `assets/js/search.js` - JavaScript for search functionality

## Usage

To use this website locally:

1. Clone the repository
2. Open `website/index.html` in your web browser
3. Navigate through the regions and cities to find storage facilities

## Development

To modify or extend the website:

1. Update the `self storage facilities uk.xlsx` file with new data
2. Run `python create_storage_directory.py` to regenerate the website
3. Test the website locally
4. Deploy the `website/` directory to your web server

## License

This project is available for educational purposes. 