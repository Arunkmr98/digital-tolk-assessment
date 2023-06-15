Do at least ONE of the following tasks: refactor is mandatory. Write tests is optional, will be good bonus to see it. 
Please do not invest more than 2-4 hours on this.
Upload your results to a Github repo, for easier sharing and reviewing.

Thank you and good luck!



Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php

Code to write tests (optional)
=====================
3) App/Helpers/TeHelper.php method willExpireAt
4) App/Repository/UserRepository.php, method createOrUpdate


----------------------------

What I expect in your repo:

X. A readme with:   Your thoughts about the code.
 What makes it amazing code. Or what makes it ok code. Or what makes it terrible code.
How would you have done it. Thoughts on formatting, structure, logic.. 
The more details that you can provide about the code 
(what's terrible about it or/and what is good about it) the easier for us to assess your coding style, 
mentality etc

And 

Y.  Refactor it if you feel it needs refactoring. 
The more love you put into it. The easier for us to asses your thoughts, code principles etc


IMPORTANT: Make two commits. First commit with original code. Second with your refactor so we can easily trace changes. 


NB: you do not need to set up the code on local and make the web app run. It will not run as its not a complete web app. This is purely to assess you thoughts about code, formatting, logic etc


===== So expected output is a GitHub link with either =====

1. Readme described above (point X above) + refactored code 
OR
2. Readme described above (point X above) + refactored core + a unit test of the code that we have sent

Thank you!


# digital-tolk-assessment

Explanation of (x): Based on the formatting of the code, it looks perfect, along with that the logic of the code depends on 
the output or the functionality of the code. However, the code is not completely or well structured in terms of defining all the different 
functions in the single repository. they must be implemented in different classes. 

If would have the chance to work with the code again, i will must separate the code based on the functionality and split the code into several shorter 
    
    1. functions 
    2. Action classes  
    3. Services.
    4. Traits
    5. Helper Methods 

like for notifications, alerts, jobs there needs to be a separate handlers.

Explanation of (y): According to the my understanding of refactoring the code i have found that the code needs to be refactored, however, 
i have covered few points in this code where i have removed commented un-usable code from the BookingRepository and also i have separated the long function for feedistance from controller to repository.


also, i have altered the code in  BookingController function(resendNotifications) where i found the duplication of code in two different methods
and combined them into one single function using parameter in the function.












