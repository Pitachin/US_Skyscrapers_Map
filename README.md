# U.S. Skyscrapers Interactive Map

This project visualizes the distribution of skyscrapers (taller than 100 meters) across U.S. states using **GeoPandas** and **Folium**.

---

## Live Map

👉 **[Click here to view the interactive map](https://Pitachin.github.io/US_Skyscrapers_Map/US_Skyscrapers_Explore.html)**

The map allows users to:
- Hover over states to see the number of skyscrapers  
- Zoom and pan across the U.S.  
- View an attractive color gradient based on skyscraper counts  

---

## Data Source

- Dataset: *Distribution_Across_USA.xlsx*  
- Contains skyscraper counts per state (compiled from StatCrunch dataset)

---

## Tools & Libraries

- [GeoPandas](https://geopandas.org/)
- [Folium](https://python-visualization.github.io/folium/)
- [Matplotlib](https://matplotlib.org/)
- [Jupyter Notebook](https://jupyter.org/)

---

## ⚙️ How to Reproduce

1. Clone this repository:
   ```bash
   git clone https://github.com/<你的用户名>/US_Skyscrapers_Map.git
   ```
2. Install dependencies:
   ```bash
    pip install geopandas folium matplotlib
   ```
3. Run the Jupyter Notebook:
   ```bash
    jupyter notebook Geographical_distribution.ipynb
   ```
4. The script will generate:
   ```bash
   US_Skyscrapers_Explore.html
   ```
   which can be opened in any web browser.
