# GenderInFilmAnalytics
Project Description
"GenderInFilmAnalytics" is a comprehensive analysis aimed at uncovering the evolution and impact of gender representation in Hollywood movies. Utilizing the Bechdel Test as a benchmark, this project dissects movie datasets to correlate Bechdel scores with IMDb ratings. Through meticulously crafted visualizations, the project reveals patterns and trends that provide insights into the industry's progression towards gender equity.

Visualizations and Insights
The following visualizations are central to our analysis:

Histograms of Bechdel Scores: Showcasing the distribution of Bechdel scores to visualize the prevalence of gender representation.
Trend Line of Movie Releases: A chronological trend of movie releases highlighting the industry's growth and possibly its changing attitudes towards gender representation.
Time Series Analysis: Displaying the number of movies passing the Bechdel test by decade, giving a historical perspective on gender portrayal progression.
Correlation Plots: Contrasting IMDb ratings with Bechdel scores to examine if there's a correlation between a film's portrayal of gender and its reception.
Director Gender Prediction: Inferring the gender of directors to discuss potential biases and its effects on the Bechdel score.
The visualizations serve to articulate a narrative about gender dynamics in film, quantifying progress and identifying areas where the industry may still be lacking.

Data Sources
The analysis leverages the following datasets:

movielatest.csv: A dataset containing current movie data.
movies.csv: Historical movie data including diverse attributes.
getAllMovies.json: A detailed metadata collection for each film.

Installation and Usage
Before running the analysis, ensure you have Python 3.x installed along with the required libraries:
pip install pandas matplotlib seaborn numpy scipy plotly express gender_guesser


To execute the script, run:
python BechdelTestFilmStudy.py

Project Structure
BechdelTestFilmStudy.py: The main Python script with data processing and analysis code.
data/: Folder containing the datasets used in the analysis.

Contributing
Contributions to "GenderInFilmAnalytics" are welcome. Whether it's suggesting new analyses, improving the codebase, or enhancing documentation, we value your input.

License
This project is open-sourced under the MIT License.

Authors
Jyeshtha Abhijit Prabhu

Acknowledgments
Special thanks to all contributors and data providers who made this project possible.
