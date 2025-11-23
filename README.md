# Assignment 2
Course: Collecting Data | Student Number: S6494935

### 1. Corpus
The corpus consists of TXT files of the lyrics of every song on the 'What Could Possibly Go Wrong' (2020) album by Dominic Fike.

### 2. Target audience and Intended Use of the Corpus
The target audience are individuals who want to examine the lyrics of the songs on that album in some way. The intended use of the corpus is to have all the lyrics in one place, so one has a clear overview of all the songs, which should make it easier to investigate the way that the songs and sentences are structured, as well as to examine which words are being used.

### 3. Text selection criteria
The following criteria applied to the selected lyrics:
1. The song was part of the 'What Could Possibly Go Wrong' (2020) album by Dominic Fike;
2. The lyrics was complete;
3. And the lyrics was scrapable using Python.

### 4. Data collection process
The following steps were part of the data collection process:
1. I scraped the lyrics using the Genius API together with John W. Miller's version of the LyricsGenius library from GitHub.
2. I assigned the scraped lyrics to the data directory.

### 5. Preprocessing
The lyrics were preprocessed as follows:
- Replaced the \n in the document with a space;
- Removed the \[song part\] from the document;
- I removed the .txt from the filenames;
- And I renamed the TXT files to only include the song title instead of also containing: 'saved_song_lyrics_dominic_fike_', in front of the song title.

### 6. (Tools Used for) Annotations
SpaCy was used to create the following annotations:
- Tokens
- Lemmas
- Parts-of-speech

### 7. Format of Files in the Corpus
The following formats are part of the corpus:
- The lyrics are in TXT format
- The data from the corpus files are in CSV format

The following columns are in the CSV file:
1. Filename
2. Document
3. Text
4. TODO: Tokens
5. TODO: Lemmas
6. TODO: Parts-of-speech