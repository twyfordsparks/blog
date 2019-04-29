# Blog

## About

Blog is a web application that allows users / writers to view and comment on blogs posted.

## 26 February 2019

## By **[John Victor Njoroge Karanja]**

## Description

Blog is a web application that provides a platform for the user to comment on blogs posted and allows writers the opportunity to create blogs.

## Specifications

### Who is the target User

* Anyone who wants to review, share , comment and advice the public.

### Front-end/User Interface Logic Objectives

* By default the page will load and provide two options and a sign up option.
* Post a Blog: This section will be used by writers who want to post a blog. You will be required to login to access this section.
* Read a Blog: This section will be used by users who want to comment on blogs.
* Sign In: This is the section to be used for signing in or creating new members.

### Back-end/Business logic Objectives

* The application is using a postgres database to store data.
* Once a user is created he / she can sign in and post or comment on available posts.

### Behaviour-Driven Development

| Behavior            | Input                         | Output                        |
| ------------------- | ----------------------------- | ----------------------------- |
| View Home | Click on the Blog | Loads the home page. |
| View Post a Blog | Click on Post a Blog | Validation helps to check if you are logged in. If yes page load else you are routed to sign in page.|
| View Read a Blog | Click on Read a Blog | No validation required. All blogs are loaded and random quotes are displayed.|

## Technologies  Used

    - Python 3.6 required
    - Flask
    - CSS
    - BOOTSTRAP 4
    - GIT

## Set-up and Installation

    - Install python 3.6
    - Run chmod a+x start.py
    - Run ./start.py

    Incase you need to access / improve the application please follow the below steps
    1.  Use this command $ git clone <https://github.com/twyfordsparks/blog.git>
        This will clone the projects repository into a local folder on your device.
    2.  Open the files with an editor( preferably  Visual Code. )
    3.  Study the code. learn from it. Improve on it.

## Known Bugs

There are no issues or bugs encountered yet while coming up with the programme but incase of anything,feel free to contact the devoloper through johnvictor0002@gmail.com.

## Support and contact details

Incase you want to use the programme and you dont know where to start or what to do,feel free to contact the developer and be sure to receive help as much as you would need.You can do so through johnvictor0002@gmail.com.

## License

*MIT LISENCE.Feel free to use the code in anyway to improve it.
Copyright (c) 2019 John Victor Njoroge Karanja.
