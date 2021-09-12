# STOPWATCH
We will import time module.
The user will press Enter to start the stopwatch. At this point start_time is set using time.time(). So, at this point, start_time has the number of seconds passed since epoch when the clock is started.
Now, the clock will run in the background.
Now the user will press Enter again for stopping the stopwatch. At this point end_time is set using time.time(). So, at this point, end_time has the number of seconds passed since epoch when the clock is stopped.
So, the time lapse can be calculated using the difference between end_time and start_time.
time_lapsed has the value in seconds. We want the output in hours, minutes and seconds. To do this we will use the user-defined function time_convert().
time_convert() will convert seconds into minutes by dividing the number of seconds by 60 and then the number of minutes divided by 60 is the number of hours.
We are printing the Lapsed time also from inside time_convert().
