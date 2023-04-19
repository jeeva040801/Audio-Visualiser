# Audio-Visualiser
The "script.js" is a JavaScript code that creates an audio spectrum visualizer using the HTML5 Audio API. It sets up an event listener to detect when a file is uploaded or dragged and dropped into the page. The uploaded file is then read and decoded into an audio array buffer which is visualized using an HTML5 canvas element.
In the Onload function we are initialising visualiser function where all the variables are initialised.
Then we make the API calls and an Event_listner is added.
In this Event_listner takes the Audio file from the user.
We connect to the analyser and the song is played. The animation is created using draw spectrum function and decoded into an audio array buffer which is visualized using an HTML5 canvas element.

In the "Index.html" we are creating a baisc structure to upload the audio files and wrapping the elements.
The <canvas> tag helps us to render 2d animations.
In the "style.css" we have positioned and provided style to the "wrapper","visualiser-wrapper" elements.