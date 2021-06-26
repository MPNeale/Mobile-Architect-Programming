# Mobile-Architect-Programming


    Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
    
      I chose to create an inventory management app. The goals of the app were to create a login screen with a database to hold user data, create a screen to show all the inventory items with a database to hold item information, have the abilitiy to add/remove/edit items on the list, and enable text message notifications if the user chooses to. My app was designed to address user needs to keep track of inventory in a home or small business.      
    
    What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
    
      My app consists of six screens, a login screen, a new user creation screen, a main screen for inventory, an add item screen, an edit item screen, and a settings screen. I tried to make navigation easy. Users have the option of clicking a button to move between screens or using the back button. I made all my buttons accessible and easy to understand their purpose, whether by putting a label on them or using easily recognizable symbols. I think my designs were successful. I gave my app to a few people to try and they were able to easily figure it out and use the app.
    
    How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
    
      I tried to take a modular approach to my coding process. I started with trying to think of all the screens I would need and designed the UI for each screen and buttons to navigate between screens. Next I went screen by screen to develop functionality. I try to get each component working properly before moving on the the next. I like working this way rather than jumping all over the place working on multiple things at once.  
    
    How did you test to ensure your code was functional? Why is this process important and what did it reveal?
    
      I found that connecting my phone with a USB and running the app on my phone worked better and was faster than using an emulator. I tested each function manually to ensure it was working properly. This works for a small app but maybe automated testing would be better for larger projects. It is important to test everything to make sure there are no flaws that might cause a fatal error. I tested different inputs for each field and discovered a few things. First I realized that you could create a new user with an empty username and password. I refactored my code to catch empty inputs and prompt the user to fill everything out. I also noticed that quantity needed to be an integer for other functionality to work. If a user entered a string or a floating point then the app would crash and keep crashing everytime it was opened. I went back and put in cases so that only an integer would be accepted as quantity input.
    
    Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
    
      My biggest challenge was understanding how to use SQLite databases and recycler view. It took a lot of reading and googling to figure out how these things worked. 
    
    In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
    
      I was particularly proud of using a recycler view to display all the inventory items. This allows a user to scroll up and down to view all their items. it was difficult to make this work and each view in the recylcer needed its own buttons. 
