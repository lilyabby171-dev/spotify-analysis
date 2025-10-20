# Understanding the Features that Drive Song Popularity
## An interactive analysis of the Spotify Tracks DB done in both Jupyter Notebook and Power BI

### Project Overview
The project explores the Spotify Tracks Database from Kaggle that spans between the years 1921 - 2020 to uncover trends and patterns behind song popularity.
Using Python (Pandas, NumPy, Matplotlib, Seaborn) and Power BI, I cleaned and analysed key audio features such as energy, danceability, valence, loudness, and acousticness to undertsand what makes songs more appealing to listeners.
The findings are visualised through interactive dashboards and charts that highlight  how these features influence track popularity.

### Data Cleaning
- The dataset was initially cleaned
- Verfied data cleaning
- Standardised column names to avoid confusion when creating dashboards

### Explaratory Data Analysis
#### Conducted EDA in Jupyter Notebook to understand distributions and relationships between features and popularity:
- Scatter plots - visualised how features such as danceability, energy, tempo and valence correlate with popularity
- Box charts - visualised the top 20 genres based on popularity
- Correlation Heat Map - visualised which features have the strongest and weakest correlations with one another

### Key Insights
- Popular songs generally have higher danceability, energy, loudness, and valence
- Most songs tend to have low acousticness and liveness
- Despite listeners having a bias for songs with higher valence, the dataset contains songs that have a lower valence, suggesting they are more neutral/sad
- Songs with higher accousticness and liveness are generally less popular amongst mainstream listeners
- Most songs have a moderate to high danceability, tempo and energy, suggesting bias towards more upbeat songs

Overall, the analysis reveals that mainstream listeners tend to favour more upbeat, energetic tracks with strong rhythmic qualities and positive emotional tones, while softer acoustic or instrumental songs occupy a smaller niche in the popularity

### Tools and Technologies
- Python - Pandas, NumPy, Matplotlib, Seaborn (cleaning and EDA)
- Power BI - Interactive data visualisation and storytelling
- Microsoft Excel - Preliminary inspection and formatting
- Dataset - Spotify Tracks DB from Kaggle

### Next Steps
- Incorporate genre and year data to analyse popularity trends over time
- Apply a machine learning model to predict song popularity
