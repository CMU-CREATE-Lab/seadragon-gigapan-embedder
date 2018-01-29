# seadragon-gigapan-embedder
A JavaScript API to view any Gigapan with the Seadragon viewer

Based off of the [seadragon gigapan viewer](https://github.com/CMU-CREATE-Lab/seadragon-gigapan), this code allows for a simple embed page that takes in two URL params. These params are:

**gigapanId**=*the id associated with a gigapan from the website (required)*

**authKey**=*an authentication key associated with said gigapan (optional)*

The embed supports both touch and mouse and can go full screen even inside an iframe (assuming the allowfullscreen attribute is used on the iframe tag).
