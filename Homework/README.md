**Findings from the dataset**

In this homework, I decided to choose the CitiBike dataset since February through end of month July, since the columns were consistent and clean. 

**Data Cleanup**
I concatenated all files through python (pandas, jupyter notebook). The python code reads all files from the folder so that any new one can be added and it would be concatenated, as long as it contains the same columns.

**Dashboard 1 - Use Trend**
Through this first dashboard, we learned that citibike usage has increased since February. A lot of the dynamics happening may be explained due to COVID. As stores started opening up, use of bikes started to pick up. Since data is not compared to last year, however, we are unable to determine if usage increased because of supply as well. 

What we did notice, however, was a shift between members and casual users. For the first time in May, casual users peaked members Because of covid and remote work, people may have cancelled their memberships and instead started opting to casual users instead.

Also, 6 pm has the highest demand of bike usage.

**Dashboard 2 - Duration vs Distance**

In this second dashboard, I did two calculated fields, one for distance and the other for duration.
I wanted to understand if there was a relationship between both and the locations at which distances were longer vs duration. What I found was that while there are more drivers in the north, drivers in the south of nyc driver longer distances. 

Also, rentals for early in the morning are longer vs those later in the evening such as 6pm. With that in mind, Citibike should always use promotional strategies geared towards time of usage, as that will impact distance and duration of trip, on average.

