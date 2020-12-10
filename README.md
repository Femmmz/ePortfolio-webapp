# eportfolio
Allows users to create accounts. Users can upload their education history, work experience, past projects and more. Employers can use the search feature to look up potential recruits and message them via the chat feature. 

Note- Currently search feature only works in the deployed link since I am currently using a Free Plan of the Algolia and Firebase spark 

## Run locally
`npm install -g firebase-tools`
cd to eportfolio
`npm install`
`npm start`

And now run in the root directory:
`firebase emulators:start`
to start the local database

## deployed link
https://eportfolio-5head.web.app/

## Visual Details

# Home page
The home page is straight forward where it guides you to sign up or log in with your google or github accounts. After you log in, you can check your profile page or your chat page.
![](images/home.png)

# Profile page
The profile page allows you to add your image, your bio, upload work history, education, projects and anything that you would want to showcase.
![](images/profile1.png)
![](images/profile2.png)


# Search 
Users can search and view other's profiles. The search can be done with a person's name or search by projects, work history and more. This allows employers to search for exactly what they are looking for.

![](images/search1.png)
![](images/search2.png)

# Messaging
Users can connect with other users via the messaging feature.  
![](images/chat.png)



