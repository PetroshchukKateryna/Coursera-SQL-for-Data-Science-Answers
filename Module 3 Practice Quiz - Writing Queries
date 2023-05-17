# Coursera-SQL-for-Data-Science-Answers
1. How many albums does the artist Led Zeppelin have?
SELECT Name, COUNT(Title)
FROM artists INNER JOIN albums
ON artists.ArtistId = albums.ArtistId
WHERE Name = 'Led Zeppelin'
Answer - 14

2. Create a list of album titles and the unit prices for the artist "Audioslave".
SELECT artists.Name, albums.Title, tracks.UnitPrice
FROM artists JOIN albums JOIN tracks ON artists.ArtistID = albums.ArtistID AND albums.AlbumID = tracks.AlbumID
Where artists.Name = "Audioslave"
Answer - 40

3. Find the first and last name of any customer who
does not have an invoice. Are there any customers returned from the query?
SELECT FirstName, LastName, InvoiceDate
FROM customers c LEFT JOIN invoices i ON c.CustomerId = i.CustomerId
WHERE InvoiceDate IS NULL

Answer - NO

4.Find the total price for each album.
SELECT albums.Title, tracks.UnitPrice, SUM(tracks.UnitPrice) AS Total
FROM albums LEFT JOIN tracks ON albums.AlbumID = tracks.AlbumID
WHERE albums.Title = 'Big Ones'

Answer - 14.85

5. How many records are created when you apply a Cartesian join to the invoice and invoice items table?
SELECT invoices.InvoiceId
FROM invoices CROSS JOIN invoice_items

Answer - 922880


