# 🎵 Tritone Data Analyst Technical Task  
## 🧭 Project Overview  
This project was completed as part of the **Tritone Analytics Data Analyst Internship Technical Task**.  
The main objective was to cross-reference unclaimed musical works with a chosen artist’s Spotify catalog using ISRC codes — showcasing data retrieval, cleaning, and analytical problem-solving abilities.

## 🎶 Artist Selected  
**Coldplay**

## 🎯 Objectives  
- Connect to the **Spotify API** to fetch the artist’s full catalog (albums, singles, EPs).  
- Extract essential metadata: *Track Name, Album, Release Date, ISRC Code*.  
- Process and clean the **unclaimedmusicalworkrightshares.tsv** dataset (~7GB).  
- Efficiently search and cross-reference ISRC codes to find unclaimed works.  
- Prepare structured and professional output in Excel and PDF formats.  

## ⚙️ Tech Stack & Tools Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python 3.10+ |
| **APIs** | Spotify Web API (via Spotipy) |
| **Data Processing** | Pandas, DuckDB |
| **File Handling** | OpenPyXL (Excel), FPDF (PDF Summary) |
| **Output Formats** | `.xlsx` (Excel) & `.pdf` (Report) |

## 🧩 Implementation Steps

1. **Spotify API Integration**  
   - Connected using `spotipy.SpotifyClientCredentials`.  
   - Retrieved Coldplay’s complete discography (albums, singles, EPs).  
   - Extracted ISRC codes for each track.

2. **Dataset Handling & Optimization**  
   - Loaded the massive TSV file (`unclaimedmusicalworkrightshares.tsv`) in **chunks**.  
   - Utilized **DuckDB** for efficient filtering and searching.  
   - Normalized ISRC codes for matching accuracy.

3. **Cross-Referencing**  
   - Compared Coldplay’s ISRC list with the unclaimed works dataset.  
   - Identified potential unclaimed or unmatched records.

4. **Output & Documentation**  
   - Exported cleaned data to Excel with structured sheets:  
     - **Sheet 1:** Artist Catalog  
     - **Sheet 2:** Matches / Unclaimed Songs  
     - **Sheet 3:** Notes and Observations  
   - Created a **PDF summary** describing the approach and tools used.

## 📊 Observations & Learnings
- Processed large datasets without memory overflow using chunked reading.  
- Gained strong understanding of **Spotify API** and ISRC-based matching.  
- Showcased the ability to structure and document real-world data analysis tasks.  
- Emphasized clean, reproducible, and well-commented Python code.

## 📁 Project Files

| File | Description |
|------|--------------|
| `main.py` | Python code for Spotify API + dataset handling |
| `Coldplay_Catalog.xlsx` | Final output Excel file |
| `Tritone_Assignment_Summary_Deepak.pdf` | Summary report |
| `requirements.txt` | List of Python dependencies |
| `README.md` | This project documentation |


## 🧾 Submission Details  
✅ Submitted to **Tritone@tritoneanalytics.co** as per official instructions.  
🗓️ Completed within 5 business days.  


## 🌐 Author

**Deepak Kumar**  
📧 [deepakkumar2.mcac2024@ritroorkee.com](mailto:deepakkumar2.mcac2024@ritroorkee.com)  
📱 7479496478  
🎓 MCA – RIT Roorkee  
💼 Aspiring Data Analyst | Python | SQL | Power BI | APIs | Tableau 


## 🏷️ License  
This project is for educational and portfolio purposes only.  
Unauthorized reuse or redistribution is not permitted without consent.
