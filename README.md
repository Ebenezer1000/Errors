# ERRORS
![image](https://github.com/user-attachments/assets/4504c421-8da9-4e9b-b80f-a97f94dd4cfb)
- The 1960 shown as the data for the odds is wrong. The data that needs to be shown there is the prize of the user related to their rebate%. What has been shown instead is the bonus group.
- Also the lost amount is wrong and irrelevant. Wrong because it is showing the prize amount instead of the user's bet amount that they lost. Irrelevant because a bet status of lost, shows the user has lost the bet amount they wagered. So repeating that data is irrelevant. 


2.  Check the bet order ID shown at the frontend and backoffice
- Frontend Order ID - B990DEF49620240916
- Backoffice Order ID - 861145480520240912
They are different. This should never happen. A bet ticket cannot have different Bet Order ID at the frontend and backend.

    Also when you look at the lottery bet record (3rd image) the username is roodev but in the bet ticket the username is Max.
    Then check the odds column in the lottery record. It is supposed to display th prize odds not the bonus group.
    
    Then if you look at the backoffice bet ticket modal (2nd image), you see the Number of bet(s) is 384 instead of 1, the bet amount is 768 instaed of 2 and the bet details is 9,5,1|9,6,4,1|9,7,3,1|9,8,2,1|9,1 instead Bull 8, if you compare the frontend bet ticket modal 
    and backoffice bet ticket modal.
    
    If you also check the draw results on both the frontend and backoffice bet ticket, you will realize they are different. The frontend has draw result of 5 5 2 8 3, and the backoffice has a draw result of 1 3 6 5 6. 


![image](https://github.com/user-attachments/assets/fd20e181-a7ad-4215-bfc8-732d6c26d8fd)
![image](https://github.com/user-attachments/assets/5210aacb-118a-4c7f-bf66-86dff92d5450)
![image](https://github.com/user-attachments/assets/28108710-197f-40ef-842f-e435fa1d8139)

