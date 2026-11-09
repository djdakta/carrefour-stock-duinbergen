# Express Duinbergen - Gestionnaire de Seuils Saisonniers

A web-based tool for optimizing stock replenishment during high and low seasons for the Express Duinbergen store.

## Features

- **Seasonal Targeting:** Switch between Winter Mode and Summer Mode to automatically adjust minimum and maximum stock thresholds based on product profiles.
- **Dynamic Calculation:** Automatically recalculates targets based on base values and predefined multiplier profiles (Summer Boost, Winter Boost, Stable).
- **CSV Import/Export:** Import your current stock list as a CSV file to recalculate thresholds, and export the modified thresholds back to a CSV for updating your inventory system.
- **Demo Mode:** Load built-in sample data to instantly test the tool's features.
- **Real-time Filtering:** Filter articles by profile type or search for specific products to see exactly what changes are being proposed.

## Technologies Used

- **HTML5:** Semantic structure.
- **Tailwind CSS:** For rapid, responsive, and modern UI styling (loaded via CDN).
- **FontAwesome:** For rich iconography (loaded via CDN).
- **Vanilla JavaScript:** Powers the application logic, CSV parsing, threshold calculations, and export functionality without any external framework dependencies.

## Usage

1. Open `index.html` in your web browser.
2. Drag and drop your inventory CSV export onto the dropzone. (The CSV should include EAN, Name, Current Min, and Current Max columns).
3. Select your target season (Winter or Summer) using the top navigation buttons.
4. Review the dynamically calculated thresholds.
5. Export the new thresholds by clicking "Exporter CSV".

*Alternatively, click "Charger la Démo Duinbergen" to test the tool with sample data.*
