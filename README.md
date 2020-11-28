# Frost2019
![Annotated visual of the musical complexity of Maroon 5 songs over time, considering the song's album and count of non-band member writers](https://github.com/danield2255/Frost2019/blob/master/imgs/Complexity_plot.jpeg)

## Description
Repo for my summer 2019 Cal Poly Frost research project advised by Professor Kelly Bodwin.

This exploration attempts to answer the reserach question **"What is the effect over time of music industry influence on musical artists, in terms of musical content?”**

By this, I meant how do the forces of the music industry business (pop culture, record labels, outside writers, etc) potentially affect the music which artists write and release. Most of this investigating is speculation, but when an artist's content changes significantly after they start taking on outside writers, this would suggest that these outside forces are influencing the artistic content. Also, this investigation was useful in highlighting similarities and differences in artist paths, revealing when some artists remain somewhat consistent versus when they change. 

## Approaches
To attempt to answer the researh question, I created subjective (but informed) measures of: 
- popularity (4 possible measures)
  - pop1 = sum(1/current_position_on_billboard * weeks_on_billboard)
  - pop2 = sum(1/current_position_on_billboard)
  - pop3 = ln(101.1- min(peak_position_on_billboard))
  - pop4 = mean(ln(101.1 - current_position_on_billboard))
- outside influence
- lyrical complexity
- musical complexity

The time frame of this project was somewhat limited, so the project didn't get to a gloabl analysis of all music artists in my dataset, but instead I decided to go deeper into a few case study artsits. I chose to involve the following artists in the study:
- Maroon 5
- Taylor Swift
- J Cole
- Foo Fighters
- Justin Timberlake
- Twenty One Pilots
- Justin Bieber
- Britney Spears

These artists were chosen because they met the entrence qualifications and represented different popular genres and musical backgrounds in the industry. 

To qualify, an artist must have: 
- appeared on the Billboard Hot 100 in the last 20 years
- released at least 3 albums
- released their first album at least 7 years ago

Because we got data from many hundreds of artists more than this small study looked at, the scrapers collect a lot of extra data which could be useful for further investigations. 

## File Descriptions
- MarkdownKnittedOutputs: Contains HTML output of the reports 
- Scrapers: Contains the notebooks used to scrape data used for the analysis
  - BillboardScraping(Charlie).ipynb: File largely authored by a previous student of the advisor, I added onto it to add more cleaning functionality, turn some items to functions, and get writing credits
  - Cleaning(Charlie).ipynb: File largely authored by a previous student of the advisor, I added onto it to add more cleaning functionality
  - OtherScrapingFrost.ipynb: Data scraper which gets data from the Grammys, Spotify, RIAA, and ultimate-guitar.com. Not all of this data is used in this project, as it was purposed for a tangent project. 
  - SpotifyClientLinker.ipynb: API calling notebook to get data from spotify. You will need personal API credentials to use for yourself. 
  - chromedriver: The selenium required executable to do automated web naviagtion
- frostFunctions.R: an R script containing all the function definitions and comment descriptions used in the analysis files
- Frost2019Analysis.Rmd: The first analysis file where much of the basis for the final report file was made
- FinalWriteup.Rmd: The formatted and finalized output, taking elements from Frost2019Analysis.Rmd
