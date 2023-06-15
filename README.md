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




