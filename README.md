# Analyse-Media-Database

![image](https://github.com/mohan-kartik/Analyse-Media-Database/assets/42971268/55baabb2-2304-4c4c-a22b-a23e551a35c4)


Using the ERD above, formulate queries to satisfy the following questions:


- What are the last name, city, state, and country of all customers who made at least one purchase and live either in Brazil or Canada? Do not list duplicates.
- What are the titles of each album and the number of tracks on each album? 
- List the number of tracks by genre, ordered from most to least, restricted to those genres for which there are at least five tracks.
- What is the average "tenure" of the employees in months, i.e., the time they have been working at our store? Use SQL to round the result to zero digit of precision, e.g., 23 instead of 23.4. Hint: SQLite does not support DATEDIFF but does support STRFTIME (see tutorialLinks to an external site.). You need to only take year and month into account.
- What are the total number of unique customers for each Brazilian state (e.g., MG, SP, etc.), ordered alphabetically by state, who made at least one purchase (i.e., do not consider customers who never made a purchase)?
- How many customers never made a purchase, i.e., they appear in the customers table but not in the invoices table.
- How many albums contain the substring "symphony" in the album title?
- What is the total "time" of all tracks per artist in hours, i.e., add up the "Milliseconds" column in tracks? Display the artist's name and the time in hours rounded to two decimals. Only consider artists who published at least one track.
- Which playlists are the longest (greater than 0), regardless of type and format? List the playlist name(s) and the time in two columns: one for hours and one for minutes.
- Which artists have composed tracks in more than three different genres? List the artists name and the number of distinct genres they have compositions in. Do not list duplicates.
