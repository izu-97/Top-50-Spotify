# Top 50 Spotify

**Mateo Izurieta**

**02-20-2017**

## Project Description

This projects tries to answer different questions such as: which countries listen to the most energetic music?, the happiest music?, etc and tries to proof the preconception that latin countries listen to the happiest and most energertic music. It also tries to find the most popular artist and genres of music in january 2020. With the data provided by spotify, which categorize each song in different parameters such as artist, genre, dB, etc. The data is displayed with help of tableau, and there is a variaty of graphs to analyse. This project also tries to confirm the question that nowadays the latin genres such as reguetton are the most listened genre around the world and this would also explain why so many international artist are starting to colaborate with latin artist.

## Questions 

- Which countries listen to the most energetic music?
- Which countries listen to the happiets music?
- Which countries listen to loudest music?
- Which artists are the most popular worldwide?
- Popularity of songs around the world
- Distribution of genre over all the top 50s playlist by country.

## Dataset

the dataset used for this analysis was build by myself using the help of this website: http://organizeyourmusic.playlistmachinery.com/ which categorize the songs data in each playlist of the spotify user. In the dataset we can find the following columns:

- Genre - the genre of the track
- Year - the release year of the recording. Note that due to vagaries of releases, re-releases, re-issues and general madness, sometimes the release years are not what you'd expect.
- Added - the earliest date you added the track to your collection.
- Beats Per Minute (BPM) - The tempo of the song.
- Energy - The energy of a song - the higher the value, the more energtic. song
- Danceability - The higher the value, the easier it is to dance to this song.
- Loudness (dB) - The higher the value, the louder the song.
- Liveness - The higher the value, the more likely the song is a live recording.
- Valence - The higher the value, the more positive mood for the song.
- Length - The duration of the song.
- Acousticness - The higher the value the more acoustic the song is.
- Speechiness - The higher the value the more spoken word the song contains.
- Popularity - The higher the value the more popular the song is.
- Duration - The length of the song.

## Workflow

After looking around the internet fot interesting databases i found the spotify organize your music tool. Since i always have been really interested in music i thought it will be interesting to do an analysis of the different music that is played around the globe divided by country

Once i found the tool i encounter the problem that the tool couldnt separete the result by country, luckily spotify has a playlist for each contry with the current most popular songs. I follow each of this playlist and download the data for each, merge them all together in a excel file, and this way i could separate the data by country.

With the database sorted i was ready to import it to tableau and start the visualizations process.

In the story we can find 6 diffetent slides which will answer all the different questions described above.

**Which countries listen to the most energetic music?**

By doing an average of the energy level of the songs by country we can clearly see that sudamerica is the continent where people listen to the most energetic music. We can also see that spain is also higlighted, which makes sense since spain is also an spanish speaking country. there seems to be a correlation between the level of energy of the songs and the spanish speaking countrys. 

Although most of the sudamerican countries are red, the country with the highest value overall is japan which i find really interesting and would like to dig deeper into the music that japans listen in another analysis.

**Which countries listen to the happiets music?**

By doing an average of the val factor by country we can see the countries that listen to the happiest music.

And once again we can clearly see that the spanish speaking countries listen to the happiest music overall. This seems to ratify the preconception that the spanish listen to the happies and most energetic music and therefore the latinos really like to dance and go out to parties.

Something interesting to take into account is that this time japan is not included in the red countries.

**Which countries listen to loudest music?**

Following the same process as in the previous questions we see that the table has turn and now the rest of the world is highlighted instead of the spanish speaking countries. This seems to suggest that all the spanish speaking countries behave really simirarly as a group.

**Which artists are the most popular worldwide?**

For answering this question we have to sum all the songs by artist woldwide. We can clearly see that Billie Eilish is the artist that is the most consistent in top 50 lists by country with a total of 126 songs in different top 50 playlsit. From this 126 if we do a count distinct we can see that this are only 6 individual songs. This makes sense since she recently won 5 grammys and that might have affect her popularity, or this could also mean that the grammys doesnt really take the music quality into account but the popularity of the artist at the time.

**Popularity of songs around the world**

Spotify provides a parameter of popularity so we can easily sort the most popular songs and see the result we got. We can see that The box is the most popular song worlwide right now. We could also filter the graph by each country and see the different results that we got.

**Distribution of genre over all the top 50s playlist by country**

We can sum the total of songs that fall into a certain genre and sum them to deduce which is the most popular genre right now around the world. After doing so we can clearly see that the latin genre is the dominant field. This can also answer the question of why so many interanational artist are colaborating with latin artists.

## Link to tableau public

https://public.tableau.com/profile/izurieta.mateo#!/vizhome/Spotify_top_50/Story1













