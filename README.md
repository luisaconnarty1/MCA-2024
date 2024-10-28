# 2557519c MUSIC CURATION AND ANALYTICS PORTFOLIO

<br></br>

# WEEK 1: BASICS OF MUSIC DATA

TASK 2: IDENTIFY A THEME FOR YOUR DATASET

For my dataset collection I am choosing the song 'Hot To GO!' released by Chappell Roan on the 11th August 2023, featuring on her debut studio album The Rise and Fall of a Midwest Princess (2023). Maimn Themes presented:

Pop music
New Digital Age (Social media)
Chappell Roan is a name and persona adopted by singer-songwrite Kayleigh Rose Amstutz. Roan is known for her theatrical, camp, and bold stage presence brought when performing her uniquw blend of pop, rock and indie sounds of music. My reasoning for choosing 'Hot To Go!' of all the songs on her discography is for its specific erruption of popularity online. This song was one of the first to bolster Roan's career through social media trends. The song has an accompanying dance Roan teaches her audiences in person at shows, and this dance is now deeply rooted in people's associations of the song even without attendance to the show through her music video and fans recodrings of concerts being shared online. I think it is very current in regards to the evolution of music data and will present new, or modern, manifestations of music data; exploring how the ever-progressing digital age is expanding the scope in defining music data, how it is collected, and further understood.



TASK 3: CHALLENGES OF WORKING WITH MUSIC DATA

GENERAL CHALLENGES:

licensing and copyright restrictions
varying qualities and formats of data
technical complexities/ challenges in attaining or disseminating files
monetary restriction
'HOT TO GO!' CHALLENGES:

The cuiltural influence extends beyond traditional music metrics like sales and streaming numbers - hard to measure these data frameworks and engagements, so risk of inconsistant or inaccurate descriptive data
There is a decentralised approach to interaction as much of the popularity is produced through User Generated Content (UGC) so Notated, acoustic and descriptive data used may not come from the direct source of the artist.
with copyright and licensing protections in place, being a recently released pop song, access to notated and acoustic data will likely cost money
CURENT MANIFESTATIONS OF DATA RELATING TO MY THEME

DESCRIPTIVE DATA

Descriptive data surrounding my chosen song can be found on multiple streaming platforms such as YouTube, Spotify, ITunes etc., providing information on length of song, title, lyrics, number of streams, date of release, liscensing, and so on. Additionally, the song has a Wikipedia page detailing similar information such as the songs producers and label. The Wikipedia page also offers background information into the writing process, composition and critical response of the song. Descriptive data can additionally include more descriptive metadata in the notated data including time scores, and keys.

NOTATED DATA

Notated formats of Data can be found on multiplke sheet music platforms online. For my project, I am purchasing an arrangement curated by ??, found and purchased on Musescore.com. However, there is a vast availability of notated data online with other websites including ultimate-guitar.com, as well as videos on social platforms such as Youtube and Tiktok displaying arrangements alongside a guided tutorial on how to play a cover of the song.

ACOUSTIC DATA

The original studio recording of 'Hot To Go!' is available on popular streaming platforms. Additionally, the music video for the song is available on YouTube. However, due to the songs popularity there are many live recordings of the song available online. Some of them are officially recorded and disseminated covers of the song by Chappell Roan, such as with her TinyDesk performance available om YouTube. However, there are also a number of recordings available to watch online of Chappell Roan's live performances of the song. There are also many TikTok videos made using the audio. The extent of acoustic data available of the song, mostly in, but not limited to, the format of live recordings, highlights the shift of the digital age and the impact of social media in the dissemination of acoustic data. For my project however, I will be purchasing the original studio recordnig of the song in ??MP3 file format??



<br></br>


# WEEK 2: TRANSCRIBING AND EDITING SHEET MUSIC

Below I have provided first, the original sheet music. Followed by how MuseScore converted it (Highlighting where there were errors).  

<img src="data/htgoriginal.jpg" alt="student1" height="1000">
<img src="data/error.jpg" alt="student1" height="1000">


Errors include:
 - Missing text at top (song title, artist, music arranger)
 - Incorrect placement of and tempo marking above bar 1 
 - Incorrect bar count
 - Missing 'INTRO' direction
 - Incorrect bar count
 - Incorrect Bar line at beginning of bar 3
 - Unnecessary inclusion of pedal marks on bars 13, 14 and 15
 - Exclusion of lyrics
 - missing all note in bars 1 and 2
 - Elongated tie linking notes on bar 10-11
 - Incorrect placement of notes on bars on the bottom line


Potential impacts:
 - As discussed in our group laboratory on Tuesday, errors in incorrect OMR engine transcription can cause multiple issues.
   
 - Overall, I would argue, my chosen piece was predominantly successful in transposing the music accurately. However, in saying that, the errors spotted still completely affect the sound of the music.
   
 - Similar issues we encountered in the group and individual lab was the tempo either not showing up or being incorrect, this would result in the rhythm of the music being off, thus making it difficult to perform correctly.
   
 - Similarly there were errors in the alignment of notes and bar-lines. This     completely affects the readability of the score and would account for a completely different reading and sound.

Additional impacts that may be experienced from inaccurate OMR scannings may include:
 - confusion with slurs, ties and ligatures in notation
 - incorrect and missin accidentals altering sound of music
 - Incorrect time signatures of keys, completely altering tonality and ability to perform a piece


# WEEK 3: ENCODING BASICS FOR NOTATION

For this weeks task we compared and analysed the difference in a MusicXML file, with an MEI file-type. My analysis and example MEI are available [here](luisaconnarty1.github.io/MCA-2024/verovio.html)


# WEEK 4: COMPUTATIONAL ANALYTICS OF NOTATED MUSIC

The features I analysed: 

- RANGE: 38
Difference in semitones between the highest and lowest pitches.

  
- MEAN PITCH: 54
Mean MIDI pitch value, averaged across all pitched notes in the piece. Set to 0 if there are no pitched notes.
  
- NUMBER OF COMMON PITCH CLASSES: 2
Number of pitch classes that account individually for at least 20% of all notes. Enharmonic equivalents are grouped together for the purpose of this calculation.


- LAST PITCH: 80
The MIDI pitch value of the last note in the piece. If there are multiple notes with simultaneous attacks at the end of the piece, then the one with the lowest pitch is selected. Set to 0 if there are no pitched notes.
  
- MOST COMMON RHYTHMIC VALUE: 0.25
The most common rhythmic value of the music, in quarter note units. So, for example, a Most Common Rhythmic Value of 0.5 would mean that eighth notes occur more frequently than any other rhythmic value. This calculation includes both pitched and unpitched notes, is calculated after rhythmic quantization, is not influenced by tempo, and is calculated without regard to the dynamics, voice or instrument of any given note.




# WEEK 5: STANDARDS IN CURATION

This week we are investigating the importance of detailed metadata in order to understand what is contained within an MEI file. 
Below is a metadata schema including data I feel is particularly relevant to be included. 

<table>
 <tr>
 <th>Metadata Element</th>
 <th>Use</th>
 <th>Relevance of inclusion</th>
 </tr>

 <tr>
  <td>Title</td>
  <td>dislays the name of the chosen song.</td>
  <td>Ensures this version is not confused with a song of the same name.</td>
 </tr>

  <tr>
  <td>Artist</td>
   <td>displays the name of the person performing.</td>
   <td>Edsures the correct singer/ performer is identified.</td>
 </tr

  <tr>
  <td>Publisher</td>
  <td>displays the name of the person/ company that published the song.</td>
   <td>Ensures the correct release/ version of the song is identified. Provides inisight into publication of the song/ a labels's history.</td>
  </tr>

 <tr>
  <td>(sub)Genre</td>
  <td>displays the genre of the song.</td>
  <td>Ensures the tone and context of a song is understood</td>
 </tr>

  <tr>
  <td>Album</td>
   <td> displasy the name of the album which the song was released in.</td>
   <td>Ensures the correct version of a song is referenced.</td>
 </tr>

 <tr>
  <td>Duration</td>
   <td> displasy the length of the song.</td>
   <td>Ensures the correct version of a song is referenced. Allows comparisons to different versions/ covers of the song.</td>
 </tr>

 
</table>






