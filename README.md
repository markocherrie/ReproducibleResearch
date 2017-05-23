# ReproducibleResearch

This is a nice structure for folders and files, a workflow developed by Susan E Johnston here:

https://susanejohnston.wordpress.com/2015/05/12/an-introduction-to-reproducible-research-in-r-and-r-studio/

On using this system for the past year, I would generally say that it is very useful and kept things organised. Some thoughts below:

It's probably worth drafting heaviliy the proposed analysis and going through before commiting to using 
the template. This is important as you don't end up with lots of temporary files and scripts, whilst you are still trying 
figure out which way is best to go. 

I would also say that it is useful to create branches at different stages of the analysis. This may be after a function that 
takes a long time to run, or where there is a big decision on the way of the analysis and you want to do some sensitivity checks.
For these branches, output back up files to be able to run without the functions previously. 

Breaks tended to occur around long functions and non-realative paths. 

Leave a significant time to clean up and streamline existing code.  
