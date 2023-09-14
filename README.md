# stopwatch
<h2 align="left">Hi 👋! My name is Apoorv</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=maurodesouza&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=maurodesouza&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

###

<img align="right" height="150" src="https://i.imgflip.com/65efzo.gif"  />

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo"  />
</div>

###

<div align="left">
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitch logo"  />
  <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
</div>

###

<br clear="both">

<img src="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/snake.svg" alt="Snake animation" />

###
The code assumes that you have HTML elements in your webpage with specific IDs: stopwatch for displaying the timer, start for the start button, stop for the stop button, and reset for the reset button. These elements are accessed using document.getElementById. Variables:

timerEl: Holds a reference to the HTML element where the stopwatch time is displayed. startButtonEl, stopButtonEl, and resetButtonEl: Hold references to the start, stop, and reset buttons, respectively. Variables for Timing:

startTime: Represents the timestamp when the timer was started or resumed. elapsedTime: Stores the total elapsed time in milliseconds. timerInterval: Stores the interval ID for the timer update loop. startTimer Function:

When the start button is clicked, this function is called. It calculates the startTime by subtracting the current timestamp from elapsedTime. This allows the timer to resume from where it left off when paused. It sets up a timer using setInterval that updates the elapsed time and displays it on the page every 10 milliseconds. It disables the start button and enables the stop button to prevent multiple timer instances from running simultaneously. formatTime Function:

This function takes the elapsedTime in milliseconds and formats it into a human-readable time format (HH:MM:SS.SS). It calculates hours, minutes, seconds, and milliseconds from the elapsedTime. stopTimer Function:

When the stop button is clicked, this function is called. It clears the timer interval using clearInterval, effectively pausing the timer. It re-enables the start button and disables the stop button to allow the timer to be started again or reset. resetTimer Function:

When the reset button is clicked, this function is called. It clears the timer interval (if running) to stop the timer. It resets elapsedTime to 0 and updates the timer display to "00:00:00". It re-enables the start button and disables the stop button. Event Listeners:

Event listeners are added to the start, stop, and reset buttons to trigger their respective functions when clicked.
