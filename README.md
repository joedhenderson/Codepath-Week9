# Codepath-Week9

CHALLENGE GOALS

1. Username Enumeration: Looking at the login screen for all the pages there were no major differences except on the green website there was a difference in the bolding of the login was unsuccessful.
 ![Alt Text](https://media.giphy.com/media/W2zoSsTOFDJE1HITln/giphy.gif)



2. Insecure Direct Object Reference: All the websites showed an ID for each person which is already bad but canbe functional but the red website when you went to ID 10 which was a non-public or supposed to be but apparently the red website did not properly have it checked to not shw whereas the other sites allowed id ten but redirected to the main salesperson page.
 ![Alt Text](https://media.giphy.com/media/keaiPWOEcf5KTWSowt/giphy.gif)


3. SQL Injection: Since most of the locations for input were sanitized one of the few places that there was not input was the url ending and it allowed you to change the salesperson through that.
 ![Alt Text](https://media.giphy.com/media/PnC0T7HYADefkF2BYY/giphy.gif)


4. Cross-Site Scripting:
  Upon looking across the site there are only a few places that a user could place info and one of them being the feedback tab. So after putting in an email and name using the script that was provided to prove it was me it was found that the green website did not properly sanitize for scripts with its feed back tab.
  
  ![Alt Text](https://media.giphy.com/media/LR13Ra9PLE6igOZlTt/giphy.gif)





5. Cross-Site Request Forgery: Because the red site does not have the certain CSRF protections it would allow any user to simply create the form to be pointed to that page could run and change the data in the pages.
![Alt Text](https://media.giphy.com/media/j29zQbS8wfRVUud0fk/giphy.gif)





6. Session Hijacking/Fixation: Since the tool has been provided it was fairly easy to see which site after leaving them on for a period of time because blue did. Red and green both required a user to log back in after whereas blue still functioned normally meaning you could log in to any previous session.
  ![Alt Text](https://media.giphy.com/media/IbgSn8nK1fdrF45ZV4/giphy.gif)
