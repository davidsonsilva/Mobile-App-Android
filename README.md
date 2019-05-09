# Mobile-App-Android
Upcoming Movies Mobile App - Android

# PROJECT DESCRIPTION

As a mobile engineer you've been assigned to the project of an app for cinephiles and movie hobbyists. The current
version (MVP) of the app is very simple and limited to show the list of upcoming movies. The app is fed with content
from The Movie Database (TMDb). There is a list of tasks that have been assigned to you, and none of them include
any design specs, so you're free to follow your UX and UI personal preferences. However the app should continue
working both in landscape and portrait orientations.

# TASKS

There are 8 tasks in total. Half of them are blockers and must be delivered - the other half is optional. Feel free to go through the tasks in any order, but make sure at least all the blockers are resolved. Also, if you feel there are other improvements the app could benefit from, don't hesitate in implementing them while you're working. 
 
# Blockers: 

  ● Implement the details screen:​ Once the user clicks on a movie, they should be redirected to the details screen. The details screen should present the following movie data: name, poster image, backdrop image, list of genres, overview, and release date. 
  ● Implement pagination:​ The list of upcoming movies currently only shows the first page of content. We want to make sure the users can see all the content by automatically requesting and showing the next pages as the user scrolls down through the movies - in an infinite scroll manner. 
  ● Remove logic from the HomeActivity:​ We currently have all our logic within our views. Since right now our logic is pretty simple, it might seem like that's not an issue. But as we grow in complexity and functionality, this might lead to several problems. We'd like to get any non-view related logic out of the view classes in order to reach a more organized and maintainable structure. 
  ● Get rid of the splash screen:​ We currently have the splash screen only for ensuring that we have the genres cached before requesting the upcoming movies. However, we came to an understanding that ​splash screens are evil​, so we want to get rid of it. We want to make sure we still properly show the movies genres in the movies list, though.
  
  
 # TECHNICAL REQUIREMENTS 
 
You should see these tasks as an opportunity to improve the app following modern development best practices (given your platform of choice), but also feel free to use your own app architecture preferences (coding standards, code organization, third-party libraries, etc). 
