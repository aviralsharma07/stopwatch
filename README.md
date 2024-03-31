# Stopwatch

In this Project, I Learned, 

1. To put an Image in the Background using CSS and to put a lower opacity layer on it.
   ```css
   background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url(./images/background.png);
   background-size: cover;
   background-position: center;
   ```
2. Use of `setInterval` and `clearInterval()` Method:
   - setInterval() repeatedly executes the specified function at regular intervals until it is stopped with clearInterval().
   - To stop execution in setInterval(), you need to call clearInterval() with the ID returned by setInterval().
   - Use setInterval() when you need to execute a function repeatedly at fixed intervals, such as updating the time on a clock or creating animations.
