Dataset Name: songAttributes.csv

Data File Description: Using the Spotify API, this is data collected about all the songs of a flexible list of particular artists. These artists in this investigation will represent various archetypes, and all of their studio discography will be included in this dataset, pulling most all of Spotify's song attributes for each of these. These attributes were attained using Daniel DeFoe's spotify API credentials. 

Columns:
	-Artist: name of the artist
	-Album: Name of the album
	-Track: name of the track
	-Popularity: spotify's popularity score for the song
	-Explicit: boolean value for if the track is explicit or not
***The next descriptions are from 'https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/'
	-Danceability: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable. 
	-Energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. 
	-Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db.
	-Mode: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
	-Speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks. 
	-Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
	-Instrumentalness: Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal”. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
	-Liveness: float	Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
	-Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
	-Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
	-Duration: The duration of the track in milliseconds.
	-TimeSignature:An estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure).



File Format: CSV or comma separated value file

Related Data Files: None

Data Owner: Spotify

Contact Person/Primary Data Investigator: Daniel DeFoe; California Polytechnic State University San Luis Obispo, California; ddefoe@calpoly.edu

Data-Collection Date: after 7/6/2019

Update dates: