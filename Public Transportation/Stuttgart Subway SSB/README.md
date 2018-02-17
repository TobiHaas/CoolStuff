# SSB / Stuttgart Subway
This board shows a departure board for the subway / Metro in Stuttgart (Germany). The API used in the board is only suitable for the Stuttgart subway.

# Remarks
To adjust the board to a different subway station, please use this URL to find our the station number (Replace the search term Eugensplatz):

http://api.peakboard.io/VVS/GetStationsBySeachTerm?stationSearchRequest.searchTerm=Eugensplatz&stationSearchRequest.boxID=123

After you found out your station number go to the JSon source in the board and replace the new station number in the URL.

The data is based on this API:

https://codefor.de/projekte/2015-06-09-stgt-efa-meta-api.html
