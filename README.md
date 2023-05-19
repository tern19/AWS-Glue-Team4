1. Immediately we run into the first issue, since the buckets names need to be unique globally, and the team who created the tutorial already used the names 'landing.zone.bucket' and 'formatted.zone.bucket' it's impossible for us to create the buckets with the same names. Thus we will use 'landing.zone.bucket1' and 'formatted.zone.bucket1'. 

![](screens/1.jpg)

After which we have uploaded the players.csv data into the landing zone bucket.

![](screens/2.jpg)

2. We then have created the AWS glue job according to the instructions

![](screens/3.jpg)

3. Then we have filled out the details of the job according to the instructions and have saved it

![](screens/4.jpg)

4. Finally we have followed the instructions for adding the steps to our ETL process and saved the outcome.

![](screens/5.jpg)

5. However when trying to run the job both times we hit an error.

![](screens/6.jpg)

As seen on the screenshot it was due to the error with the FillMissingValues element of our ETL process. After removing it from the ETL flow, the job finished successfully.

![](screens/7.jpg)

We made sure that it worked correctly by checking the formatted zone bucket, and it indeed had now newly created parquet files as intended.

![](screens/8.jpg)

All in all, it was a fairly well structured, albeit a little simple, tutorial on using a new tool that was previously unknown to us. I would give this an 8.5 as the score. 