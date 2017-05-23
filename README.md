<b><h2> Reproducible research </h2></b>

I came across an R workflow developed by Susan E Johnston here:

https://susanejohnston.wordpress.com/2015/05/12/an-introduction-to-reproducible-research-in-r-and-r-studio/

In this folder I have put in the structure that she suggests, which I have adopted in my own research over the past 12 months.

I would generally say that it is very useful and kept things organised. Some thoughts below:

It's probably worth drafting heaviliy the proposed analysis and going through before commiting to using 
the template. This is important as you don't end up with lots of temporary files and scripts, whilst you are still trying 
figure out which way is best to go. 

I would also say that it is useful to create branches at different stages of the analysis. This may be after a function that 
takes a long time to run, or where there is a big decision on the way of the analysis and you want to do some sensitivity checks.
For these branches, output back up files to be able to run without the functions previously. 

Be very strict with yourself on using relative paths, although sometimes it is inevitable if you are working on data that needs to be on secure networked location.

I've added files for descriptive statistics and vizualization, which I think are better to keep seperate from do.R which is where the main analyses go. 

Prioritise putting in interpretation of graphs and and tables as you go along; this helps to keep co-authors up to date on your progress.

Leave a significant time at the end to clean up and streamline existing code.  

Here are some other tips:

http://blog.revolutionanalytics.com/2010/10/a-workflow-for-r.html 

https://stats.stackexchange.com/questions/2910/how-to-efficiently-manage-a-statistical-analysis-project/3191#3191

