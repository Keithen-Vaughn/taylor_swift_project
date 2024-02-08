# taylor_swift_project

Dataset provided on Kaggle by Jarred Priester - https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset

In this project I will be using microsoft excel and google sheets to clean data, examine the data to see if its possible to predict popularity of songs based off of track metrics, and also visualize my findings.

Data Cleaning Steps
  1) Checking to find any empty cells using =ISBLANK(), there were none besides the fully empty rows 532-1000(after the data table). I proceeded to deleted the empty rows at the end of the data table.
  2) I changed the duration from milliseconds to a minute:second format. I did this by dividing the ms by 1000 to change the unit to seconds. I then divided the seconds by 86400 to get the numbers into an hour form. Once I did that I used a custom number format to display it.
  3) 
