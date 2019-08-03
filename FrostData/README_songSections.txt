Dataset Name: songSections.csv

Data File Description: Scraped data from ultimate guitar tabs website. Will be used on the songs which appear on the Billboard Hot 100 and are by one of the archetype representative artists (assuming a tab is available). Separated by section of the song and tracks musical data. 

Columns:
	-Title: song title
	-Arist: name of the artist
	-Section: name of the section if known
	-Progression: chord progression in numbers in the key of C major
	-EndDifferent: ‘None’ if the section is completely consistent, otherwise, a string of chord progression in numbers in the key of C major of the end of a section if it differs from the progression
	-ExtendedChords: number of chords with an extension (C7 or C9)
	-NonDiatonic: number of non-diatonic chords (chords outside of the key, here the key of C)  used in the section
	-NumChords: number of unique chords used in the section


File Format: CSV or comma separated value file

Related Data Files: None

Data Owner: UltimateGuitarTabs.com

Contact Person/Primary Data Investigator: Daniel DeFoe; California Polytechnic State University San Luis Obispo, California; ddefoe@calpoly.edu

Data-Collection Date: after 7/6/2019

Update dates: