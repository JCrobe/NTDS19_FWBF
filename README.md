![alt text](https://github.com/JCrobe/NTDS19_FWBF/blob/master/FWBF_NTDS_Graphics.png)

# Abstract
Music  is  something  universal  and  has  beenknown  for  connecting  people  for  a  long  time.   
In the age when diversity in music industry is at its peak, it seems that music has lost its universality and people’s musical taste varies to a great extent.

In this project:

* We seek to analyse whether music truly connects people and how one’s musical taste is reflected in one’s friendship network.  
* Using network analysis tools, we want to understand if real friends are common to have the same taste in music.
* We compare the social and music networks and represent the similarities among them.
* We suggest a tool that can be used by artists and music producers to estimate how popular their music track will be before they even release it.


# Dataset
For the first part of the project, 'Your top Songs of 2018' Spotify playlists of 23 volunteer users were scraped using Spotify API and Spotify package in python.
A dataset of 1274 artists and 2207 songs was created consisting of features as artist,  genre,  track  duration, musical characteristics such as acousticness, tempo,liveliness, danceability, key, loudness etc.

For the second part of the project —track popularity prediction, dataset  of  an  interactive,  audio  downloads  library  called  Free  Music  Archive(FMA)  was  used.   
In  particular,  per track  metadata such as ID, title, artist, genres and play counts along  with  audio  features  provided  by  Echonest(now Spotify) of 13,129 tracks were used.
The data can be accessed at [this link](https://github.com/mdeff/fma).

# Our final data story:
A full report of our work as well as the code for data scraping, preprocessing, network analysis and predictions can be found on our [github repository](https://nicolasfontbonne.github.io/).
We hope you'll enjoy exploring it!


# Team members:

* Tobias Barblan
* Laura Bujouves
* Liana Mehrabyan
* Jeremy Wanner

# Acknowledgements
A final word for the amazing working team of the NTDS course at EPFL: our professors- Frossard Pascal, Vandergheynst Pierre, head TA Michael Defferrard and others, thank you!
# NTDS19_FWBF
