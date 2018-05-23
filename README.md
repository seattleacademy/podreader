# podreader
A tool for playing mp3 audio from a podcast along with its transcripts
# objective
The goal of this project is help lanaguage learners follow along with a podcast and transcript with phrases hilighted and replayed when clicked on (or on keyboard control), allowing for the playback rate to be adjusted (playbackRate property), translation of phrases available on request, pictures displayed when phrases are read, etc.

Upon mp3 and transcript uploaded, the software will divide the text into phrases (blocks separated by punctuation including , ; , ? and !.  Then the user will listen to the podcast and use the keyboard to mark the timestamps into a database (mongodb) to sync the mp3 with the phrases.  Upon rereading, audio can be paused at phrases, slowed down (or spead up), replayed, etc., optionally picutures that the user selects (give a URL for) can be displayed and/or a translation can displayed along side.

Technolgoy used will be html (with focus on advanced audio tag features) and selectable text, mongodb for storing timestamps/phrases/links to pictures, etc. and node.js for any serverside code.
