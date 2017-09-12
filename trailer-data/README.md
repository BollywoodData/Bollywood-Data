## Bollywood Movie Data 

This repository contains the gender and emotion data for all Bollywood Movie Trailers released from 2008 to 2017. 

The following dataset includes the folder :
- __individual-trailer-data__: It has the gender data and emotion data detected at each frame for the trailer video.

The repository also includes the following files :
- __trailers_list.csv__: Contains movie names and year of release of all the trailers in the dataset
- __complete-data.csv__: It has gender and emotion information for each of the trailers in the data folder. It has the following columns :
  - frame_number - the frame number of the trailer in which emotion and gender detection occurred
  - man/woman - whether the detected person was a man or a woman
  - emotion - the emotion potrayed by the man/woman detected in the image
  - year - the year in which the movie was released
  - movie_name - the name of the movie
- __indiviual-trailer-data.zip__ : Compressed and zipped file of all  indidividual trailer's data.

### Example
- Consider the following:
  - Movie Name - Raees
  - Year of Release - 2017
- The gender and emotion information for each frame whenever the detection was successful can be found in the folder by the name 2017-raees in the individual-trailer-data folder. This folder has a .csv file which has all the data. (Eg - data/2017-raees/2017-raees.csv)

### More information
- 880 data files for each trailer
