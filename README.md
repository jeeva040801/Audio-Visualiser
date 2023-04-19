# Audio-Visualiser
The Audio Visualiser is implemented using following Frontend technologies: HTML5,CSS and JavaScript.

The "script.js" is a JavaScript code that creates an audio spectrum visualizer using the HTML5 Audio API. It sets up an event listener to detect when a file is uploaded or dragged and dropped into the page. The uploaded file is then read and decoded into an audio array buffer which is visualized using an HTML5 canvas element.
In the Onload function we are initialising visualiser function where all the variables are initialised.
Then the API calls and an Event_listner is added.
In this Event_listner takes the Audio file from the user.
 The analyser is connected and the song is played. The animation is created using draw spectrum function and decoded into an audio array buffer which is visualized using an HTML5 canvas element.

In the "Index.html" a baisc structure to upload the audio files and wrapping the elements is created.
The <canvas> tag helps us to render 2d animations.
 The "style.css" is used to position and provide the style to the "#wrapper","#visualiser-wrapper" elements.

Use the test audio files  from test_file/ to upload and check the implementation.
