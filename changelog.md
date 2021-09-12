# 12-09-2021

- Removed the Album art and replaced it with a CD icon (TODO: Get Album art back in there)
- If the app finds any IDv3 music meta information in the file it will parse the data and display it on the app.
- Allows the user to browser for an audio file to play.
- When user clicks the play button it changes to the pause icon and vice versa.


# 07-09-2021

- Removed borders and window from the native window. This allows for a custom window border.
- Moved the functionality from the test `play` link, into the play button on the interface bar to the bottom.
- Fixed the Progress bar. Progress bar now responds correctly to the audio playing.
- Created functions to calculate minute && second time from the given seconds. (func: convertToTime)
- Imported TailwindCSS, FontAwesome. 