# Time of Day (ToD) Timing
When most people think of timing, they think of the type of timing done with a stopwatch. When a racer starts the timer starts counting up, and when they cross the finish it stops. Ski racing, however, uses what is called Time of Day or ToD timing.

Time of Day timing uses a timing device synced to local time to mark the exact time of day a racer leaves the start, and the exact time of day they cross the finish. For example:

| Event | ToD |
| ------ | ------ |
| Start | 10:31:19.8732 |
| Finish | 10:32:02.6981 |

The racer's net time is then calcuated by subtracting the start ToD from the finish ToD.

| | |
| :---: | ---: |
| | 10:32:02.6981 |
| - | 10:31:19.8732 |
| = | 42.8249 |
       
Modern electronic timing software performs this subtraction automatically. A later section of this book will explain how to subtract time by hand.

There are several major advantages to using ToD timing: 
 - It allows to easily time multiple racers on course simultaneously
 - It allows the timer to catch and correct any errors, such as false starts or false finishes, that may arise.
 
 Here is our above example, but with a second racer on course:
 
| Bib Number | Event | ToD | Notes |
| ------ | ------ | ------ | ------ |
| 1 | Start | 10:31:19.8732 | |
| 2 | Start | 10:31:49.5472 | |
| 1 | Finish | 10:32:02.6981 | *Net time 42.8249* |
| 2 | Finish | 10:32:30.9953 | *Net time 41.4481* |

And a third:

| Bib Number | Event | ToD | Notes |
| ------ | ------ | ------ | ------ |
| 1 | Start | 10:31:19.8732 | |
| 2 | Start | 10:31:49.5472 | |
| 1 | Finish | 10:32:02.6981 | *Net time 42.8249* |
| 3 | Start | 10:32:20.4762 | |
| 2 | Finish | 10:32:30.9953 | *Net time 41.4481* |
| 3 | Finish | 10:33:02.0416 | *Net time 41.5654* |

ToD timing allows for easy tracking of multiple racers, and an easy audit of the race afterwards. 
Here is an example of what might happen in the case of an error, this time a false finish:

| Bib Number | Event | ToD | Notes |
| ------ | ------ | ------ | ------ |
| 1 | Start | 10:31:19.8732 | |
| 2 | Start | 10:31:49.5472 | |
| 1 | Finish | 10:32:02.6981 | *Net time 42.8249* |
| ~~2~~| ~~Finish~~ | ~~10:32:04.6072~~ | ~~*Net Time 14.0600*~~ **FALSE FINISH** |
| 3 | Start | 10:32:20.4762 | |
| 2 | Finish | 10:32:30.9953 | *Net time 41.4481* |
| 3 | Finish | 10:33:02.0416 | *Net time 41.5654* |

Using a stopwatch, catching and correcting a false finish would be incredibly difficult if not impossible. With ToD timing the correction is straightforward, even long after the false finish occured.
