# taylor_swift_project

Dataset provided on Kaggle by Jarred Priester - https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset

In this project I will be using microsoft excel and google sheets to clean data, examine the data to see if its possible to predict popularity of songs based off of track metrics, check correlations, and also visualize my findings.

Data Cleaning Steps (Clean data on Sheet 2)
  1) Checking to find any empty cells using =ISBLANK(), there were none besides the fully empty rows 532-1000(after the data table). I proceeded to deleted the empty rows at the end of the data table.
  2) I changed the duration from milliseconds to a minute:second format. I did this by dividing the ms by 1000 to change the unit to seconds. I then divided the seconds by 86400 to get the numbers into an hour form. Once I did that I used a custom number format to display it. I hid the old column with the time in ms.
  3) I removed the first column of the dataset as it wasn't needed.
  4) I altered the headers of each column to make it more readable.
  5) I hid column E and F as they will not be necessary for the predictions I am looking to answer.
  6) I checked the min/max for Popularity column to make sure it fell between the ranges of 0-100.
  7) I checked the min/max for the metric columns (besides Loudness and Tempo) to make sure they fell between 0-1.
  8) I checked the min/max for the Loudness column to make sure it was between -60 and 0.
  9) I checked the min for the Tempo column to make sure it was above 0.
  10) Checked for duplicates to remove.

I created a pivot table (Sheet 3) to perform my analysis of the data and create visualizations.

Correlations:
  * Positive link between loudness and energy.
  * No correlation between danceability and popularity.
  * No correlation between tempo and popularity.
