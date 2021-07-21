# DeadGuy

An Arduino MP3 player that only plays the Greatful Dead

## Repo structure

* test: code to test the Catalex chip


## Design

### Parts


### Plan

* The Catalex serial mp3 player can probably only have 8-bit song and folder titles
	* For the device to hold every dead song, we will need to use all the folder and song ids giving 65,536 possible songs
* The Catalex device cannot give us the file names (unfortunately), so if we want metadata, we will need to use a different SD card
	* It is possible to encode dates into the the folder-fild-id 
		* For example, Dead performed for 30 years. The 65,536 song total would allow for almost 6 (5.985) shows per day



