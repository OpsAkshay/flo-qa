# Flo QA — Performance Yield Dashboard

An interactive performance dashboard for analyzing site metrics before and after the June 10, 2026 transition.

## Features

- **Interactive Metric Selection**: Toggle dynamically between *Programmatic Session RPM*, *Sessions*, *OE Revenue*, *Impressions per Session*, *OE CPM*, and *OE RPM*.
- **Property Filtering**: Switch views between the **Grand Total** aggregate and individual domains:
  - FloBikes (`www.flobikes.com`)
  - FloHockey (`www.flohockey.tv`)
  - FloRacing (`www.floracing.com`)
  - FloTrack (`www.flotrack.org`)
- **Data Visualizations**: Built-in toggleable *Daily Trend Line Chart* (with transition date marker) and *Before vs. After Comparison Bar Chart* powered by Chart.js.
- **Dynamic Insights**: Automatically updates domain-specific explanations for the yield variances.
- **Responsive Premium Theme**: Modern dark-mode layout with custom typography (Outfit & Inter) and glassmorphic UI cards.

## How to Deploy to GitHub Pages (`github.io`)

This project is fully self-contained in a single `index.html` file. You can deploy it to your public GitHub Pages in less than a minute:

1. **Create a New Repository on GitHub**:
   - Go to [github.new](https://github.new)
   - Name the repository `flo-qa`
   - Keep it **Public** (required for free GitHub Pages)
   - Leave "Add a README", "Add .gitignore", and "Choose a license" **unchecked**
   - Click **Create repository**

2. **Link and Push Your Local Code**:
   - Open your terminal and run the following commands (replace `<your-username>` with your actual GitHub username):
     ```bash
     cd "/Users/akshay/Desktop/mile_analysis"
     git remote add origin https://github.com/<your-username>/flo-qa.git
     git branch -M main
     git push -u origin main
     ```

3. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub: **Settings** -> **Pages** (under the "Code and automation" section).
   - Under **Build and deployment**, set **Source** to `Deploy from a branch`.
   - Set **Branch** to `main` and the folder to `/ (root)`.
   - Click **Save**.

Within 1–2 minutes, your dashboard will be live at:
`https://<your-username>.github.io/flo-qa/`
