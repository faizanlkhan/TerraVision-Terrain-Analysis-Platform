# 🗺️ TerraVision – Terrain Analysis Platform
A S-a-a-S for generating **2D elevation maps**, **3D terrain surfaces**, **erosion-risk maps**, and **landform classifications** directly from **GeoTIFF DEM files** — all using **pure JavaScript**, Plotly, and GeoTIFF.js.

This visualizer (SaaS) is an upgraded JavaScript version of the Python-based DEM visualizer I have already published on GitHub.

---

## 📌 Features
- 🗺️ **2D Elevation Map** with contour lines (Plotly heatmap + contour)
- ⛰️ **Interactive 3D Terrain Viewer** using Plotly Surface
- 🌧️ **Erosion Risk Mapping** using slope-derived risk levels
- 📊 **Elevation Statistics Table** (min, max, mean, median, std dev, slope, aspect, etc.)
- 🌄 **Landform Classification** (emoji-coded: lowland, hilly, mountainous)
- ⚡ **Automatic downsampling** for very large TIFF files
- 🧭 **Coordinate-aware visualization** (longitude/latitude axes)
- 💻 **Runs fully in the browser** — no backend required

---

## 🧠 How It Works
1. User uploads a **GeoTIFF DEM** file  
2. The file is decoded client-side using **GeoTIFF.js**  
3. Elevation data is downsampled for efficient visualization  
4. Multiple visual layers are generated:
   - 2D heatmap with contours  
   - 3D terrain model  
   - Erosion-risk map  
   - Landform classification  
   - Elevation statistics table  
5. All plots rendered with **Plotly.js**

---

## ▶️ Running the Visualizer
Open the HTML file in any modern browser.

Upload any `.tif` / `.tiff` DEM file via the interface.

Works with:
- Lunar DEMs  
- Earth SRTM  
- LRO LOLA terrain  
- Lidar elevation models  

---

## 🛠️ Technologies Used
- **JavaScript (ES6)**
- **Plotly.js**
- **GeoTIFF.js**
- **Pyodide**
- **HTML5**

---

## 🏔️ Outputs Generated
- 🟩 2D elevation heatmap with contours  
- 🟪 Interactive 3D terrain visualization  
- 🟧 Erosion-risk map (low / medium / high)  
- 🔢 Elevation statistics table  
- 🌍 Landform classification using emojis  

---

