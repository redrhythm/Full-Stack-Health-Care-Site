# Full-Stack-Health-Care-Site
This site is running, but is currently incomplete.  I have spent the past couple weeks designing and implementing it.  Kaesar Health Care is a simple prototype for a private health care facility.  This project contains a data model and database design along with specifications on columns and constraints.  This is a 3-tier architecture using the LAMP environment to implement this application.  The site is designed to enable the user to create an account (Provider/Patient) while using sessions to maintain state.  While signed in, users are able to create appointments, view their schedules, and make necessary changes/cancellations.  The assumptions are as follows:  Users are required to provide basic contact information during sign up (name, email, address, etc.). Days and times of availability will be according to company policy first, and then provider preference.  Appointment times will start on the hour, for one hour.  I also have a few ideas for the next update that I may provide in the future.  

Key things to consider:<br/>
______________________________________________________________________________________________________________________________
*Need to implement strategies for XSS prevention  <br/>
*Need to implement more secure handling of sessions <br/>
*Database missing necessary locking strategies <br/>
*Create a more readable and efficient coding environment <br/>
<br/>
Additional considerations: <br/>
*SEO <br/>
*Implement a more appealing interface <br/>
______________________________________________________________________________________________________________________________

If you would like to visit this site, feel free to copy and paste the following URL into your address bar:<br/> http://callisto.lasierra.edu/scurtis
