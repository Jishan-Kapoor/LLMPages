# Static Web Application for Multidisciplinary Content

## Summary
This static web application serves a collection of creatively diverse content files, including a short story, ethical dilemma analysis, personal descriptions, an SVG illustration, and JSON data related to various topics such as autonomous vehicles and economic predictions. These files are hosted on a GitHub Pages site, demonstrating the versatility of static content deployment.

## Setup
To deploy this application on GitHub Pages, follow these steps:

1. **Clone the Repository**: Clone the repository from GitHub to your local machine.
   ```sh
   git clone https://github.com/<username>/static-web-app.git
   ```
2. **Switch to the Repository Directory**:
   ```sh
   cd static-web-app
   ```
3. **Create a 'gh-pages' Branch**:
   ```sh
   git checkout -b gh-pages
   ```
4. **Push the 'gh-pages' Branch to GitHub**:
   ```sh
   git push -u origin gh-pages
   ```
5. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Navigate to `Settings` > `Pages`.
   - Under 'Source', select the `gh-pages` branch and click 'Save'.

## Usage
- **Accessing the Page**: Navigate to `https://<username>.github.io/static-web-app` to access the homepage linking to all content files.
- **Query Parameters**: No specific query parameters are required. Simply click on links provided on the homepage.
- **Features**:
  - **ashravan.txt**: An engaging short story exploring post-restoration Ashravan.
  - **dilemma.json**: Presents an ethical vehicle dilemma with reasoning.
  - **about.md**: A succinct, three-word self-description.
  - **pelican.svg**: Illustrative SVG of a pelican bicycle ride.
  - **restaurant.json**: A curated restaurant recommendation in Bangalore.
  - **prediction.json**: Economically insightful interest rate forecast for 2025.
  - **uid.txt**: Attached unique identifier file.

## Code Explanation
- **HTML Implementation**: The `index.html` serves as the homepage, containing links to each of the content files. It is a simple HTML page with headings and descriptive text.
- **Libraries**: No external libraries are used; this is a purely static application using HTML and SVG.
- **Logic**: The main logic resides in simple, descriptive navigation through GitHub-hosted files, without interactive or dynamic script content.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.