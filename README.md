# Jobbox-CMD
A browser command box utility using the Jobbox API.

This applications was developed during SIFO's startup rush. 
http://www.sinfo.org/

The Jobbox API is available at:https://github.com/JOBBOX/jobbox-api

Jobbox is an awesome site where you can apply to jobs. Check their website at https://www.jobbox.io/offers.

What does the app do?

The app features an AJAX implementation of some of the GET requests available in the API provided. It features a simplistic command box where you can call this request and print them on the command box. Currently the API provides read only functions.

What's there to improve?

First, the entire script is just one big file. Splitting it int a more organized HTML, CSS and Javascriot files would be awesome.

The ajax request and write on cmd are just one function. Ideally they should be two decoupled functions.

Some commans are really slow because each request envolves dozens of sub-requests. A better solution is needed. E.g.: GetJobsbyID

This readme is bad. 



