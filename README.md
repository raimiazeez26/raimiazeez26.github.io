# Raimi Azeez Babatunde — Portfolio Website

Personal portfolio website for **Raimi Azeez Babatunde**, a data scientist, financial analyst, and Python algorithmic trading developer based in Lagos, Nigeria.

- **Live site:** https://raimiazeez26.github.io/
- **Repository:** https://github.com/raimiazeez26/raimiazeez26.github.io
- **Primary technologies:** HTML, CSS, SCSS, JavaScript
- **Hosting:** GitHub Pages

## About the site

This is a static, single-page portfolio built with HTML, CSS/SCSS, and client-side JavaScript. It introduces Raimi's background and skills, presents selected projects, summarizes education and experience, and provides contact and social links. The repository also contains standalone blog layout pages.

The interface uses the Bootstrap-based Colorlib theme and supporting front-end libraries. The page is designed to work on desktop and mobile browsers.

## Sections

- **Home:** Introductory profile and links to the project portfolio and contact section.
- **About:** Professional overview, contact details, and social profiles.
- **Skills:** Data science, analytics, finance, and software skills.
- **Resume:** Education, professional experience, and certifications.
- **Services:** Data science, dashboard, web scraping, trading automation, and analytics offerings.
- **Projects:** Selected work and links to articles, dashboards, notebooks, applications, and source code.
- **Contact:** Email, phone, location, and portfolio links.

## Featured projects

| Project | Focus | Link |
| --- | --- | --- |
| Personal Portfolio Website | Responsive static portfolio built with HTML, CSS/SCSS, JavaScript, and GitHub Pages | [Repository](https://github.com/raimiazeez26/raimiazeez26.github.io) |
| Image Recognition | Machine learning with satellite imagery | [Kaggle notebook](https://www.kaggle.com/code/raimiazeezbabatunde/understanding-amazon-from-space) |
| Stock Price Prediction | LSTM time-series analysis | [Article](https://medium.com/insiderfinance/stocks-price-prediction-using-lstm-cc331e86d37f) |
| Suicide Data Analysis & Tweet Prediction | NLP and text analysis | [Article](https://medium.com/@raimiazeez26/suicide-data-analysis-tweet-prediction-9aea970c6939) |
| MT5pyTrader | Python algorithmic trading module for MetaTrader 5 | [GitHub](https://github.com/raimiazeez26/MT5pytrader) |
| Customer Segmentation | Clustering and interactive data science | [Project app](https://raimiazeez-080d78fbc4ba.herokuapp.com/app-clustering) |
| Russian Electricity Market Analysis | Financial time-series analysis | [Article](https://medium.com/@raimiazeez26/the-russian-electricity-trading-market-a-time-series-analysis-feb98c92bf0e) |
| Dow Jones Dashboard | Historical prices and technical analysis | [Tableau](https://public.tableau.com/app/profile/raimi.azeez.babatunde/viz/DailyHistoricalPrices/DowJonesTechnicalAnalysis2) |
| EMA Crossover Trading Script | Python algorithmic trading | [Article](https://medium.com/insiderfinance/creating-a-simple-ema-cross-strategy-trading-script-using-mt5pytrader-c1f9e1b6a17b) |
| COVID-19 Timeline | Data analysis and visualization | [Project app](https://raimiazeez-080d78fbc4ba.herokuapp.com/app-covid) |

> Some project demonstrations are hosted by third-party platforms. Availability may depend on those services.

## Repository structure

```text
.
├── index.html              # Main portfolio page
├── blogSection.html        # Blog listing template/page
├── single.html             # Individual blog article template/page
├── css/                    # Stylesheets and vendor styles
├── scss/                   # SCSS source styles
├── js/                     # Page behavior and vendor scripts
├── images/                 # Profile and project imagery
├── fonts/                  # Icon and typography fonts
└── assets/                 # Supporting assets and vendor resources
```

## Run locally

No build step is required for the current static site.

1. Clone the repository:
   ```bash
   git clone https://github.com/raimiazeez26/raimiazeez26.github.io.git
   cd raimiazeez26.github.io
   ```
2. Open `index.html` directly in a browser, or serve the directory with any static web server. For example:
   ```bash
   python -m http.server 8000
   ```
3. Visit `http://localhost:8000`.

## Deploy

This repository uses the GitHub Pages user-site naming convention. Publish the `main` branch from the repository's GitHub Pages settings; updates pushed to the publishing source are served at **https://raimiazeez26.github.io/**.

## Editing content

- Update headings, profile text, project links, education, experience, and contact details in `index.html`.
- Keep project card image paths relative to the repository root (for example, `images/stock_predict.png`).
- Add or replace static assets in `images/`, `css/`, `scss/`, or `assets/` as appropriate.
- Keep external project URLs current and ensure new image filenames match their references.

## Credits and licensing

The visual design is based on the Colorlib template linked in the site's footer. Review the original template license and attribution terms before removing or changing that attribution. Third-party libraries and assets retain their respective licenses.
