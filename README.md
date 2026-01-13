
# Lake City Access Map

Enhanced service area analysis for grocery and pharmacy access in Lake City, Seattle.


## Walkability Data Generation

This project uses the RadiusMapper API to generate walking route polygons for store accessibility analysis. **RadiusMapper API Key**: [https://radiusmapper.com/](https://radiusmapper.com/)


## Deployment

### GitHub Actions Deployment
The changes from next.js app automatically deploys to GitHub Pages within this repo when you push to `main` or `bugfix` branches.

**Deployment Process:**
1. Push changes to `main` or `bugfix` branch
2. GitHub Actions builds the app with environment variables
3. Deploys to external repository: `Abiaina/grocery-pharmacy-access-map-site`
4. Site is live at `https://grocerypharmacyaccess.org`


This project is licensed under the MIT License.
