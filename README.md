#YouTuber Data Analysis Streamlit App

**Project Overview**  
The YouTuber Data Analysis app is a Streamlit-based application designed to provide insights into YouTube channels from the dataset `Youtuber.csv`. The app allows users to explore various statistics about YouTubers, including subscriber counts, average views, and content types. It also integrates Sweetviz for generating a comprehensive report on the dataset.

**Features**  
- **Interactive Dashboard**: Users can visualize and explore YouTuber statistics with various charts, including grouped bar charts and histograms.
- **Data Analysis**: Analyze the distribution of YouTubers across countries, calculate averages of subscribers and views based on content types, and display insights about missing values.
- **Sweetviz Integration**: Generate an interactive HTML report that provides a detailed overview of the dataset, including comparisons and visualizations.

**Requirements**  
- Python 3.7+
- Libraries:
  - Streamlit
  - Pandas
  - NumPy
  - Matplotlib
  - Sweetviz
  - Pyngrok

**Installation Instructions**  
1. **Clone the repository**:
   ```bash
   git clone https://github.com/SadafHabibb/Youtuber-Data-Analysis.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Youtuber-Data-Analysis
   ```
3. **Install the required libraries**:
   ```bash
   pip install -r requirements.txt
   ```

**Running the App**  
1. Start the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. **Expose the Streamlit app using LocalTunnel**:
   ```bash
   npx localtunnel --port 8501
   ```
   This command provides a public URL to access the app.

3. **Sweetviz Report**:  
   - A Sweetviz report will be generated automatically and saved as `report.html`. Open this file in your browser to view the dataset analysis.

**Data Description**  
- The dataset `Youtuber.csv` contains information about various YouTube channels, including subscriber counts, average views, content types, and the country of origin.

**Future Enhancements**  
- Add more advanced visualizations (e.g., time series analysis of subscriber growth).
- Implement filtering options for analyzing specific content types or countries.
- Expand data processing to include additional metrics like engagement rates.

**License**  
This project is licensed under the MIT License. See the LICENSE file for details.
