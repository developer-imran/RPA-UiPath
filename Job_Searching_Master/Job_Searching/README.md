# RPA-UiPath

Job Searching, Designed by using REFramework and Orchestrator.

=> Steps to be executed by this Process.

1) Process is designed for job seeker, Framework will collect Job Profile and Description of Openings in certain companies.
2) Process required two things 1)Key Skills and 2)Location, where candidate want to look into.
3) We will Dispatch key skills and location using Dispatcher to control room.
4) Than Framework will grab login info where we stored into asset credentials and login into naukri.com.
5) After successfully log in, process will get Queue items, i.e Key skills and location, and it will search for that.
6) After result appearance, process try to click on every single result one-by-one and grab the Job profile and Job description and closes that Tab.
7) Next after scraping profile info process will create a dynamic folder by taking key skills and location and Current time.
8) The scrape data file will be saved into that particular key skill folder.
9) After Successful Transaction of all Queue items Framework will Exit from application, the data will be saved in the Project folder "ScrapeDataResults".


check out repository contents.

