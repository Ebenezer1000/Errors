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
    
    If you also check the draw results on both the frontend and backoffice bet ticket, you will realize they are different. The frontend has draw result of 5 5 2 8 3, and the backoffice has a draw result of 1 3 6 5 6. How can this be? This needs to be fixed.
    The Issue numbers on the frontend and backoffice is also different.
    The Game type on the frontend needs to be Bull Bull not Bull 8. Bull 8 is the bet detail. And the backoffice Game type should be Bull Bull not All 5 Straight Joint.


![image](https://github.com/user-attachments/assets/fd20e181-a7ad-4215-bfc8-732d6c26d8fd)
![image](https://github.com/user-attachments/assets/5210aacb-118a-4c7f-bf66-86dff92d5450)
![image](https://github.com/user-attachments/assets/28108710-197f-40ef-842f-e435fa1d8139)




3.   ## BOARD GAMES


## PK 10 Board Game


![image](https://github.com/user-attachments/assets/a0c30e44-476a-445b-961d-d702c7b8d22f)

When you click on the bet confirm for PK10 Board game, it does not go through or it is not accepted. It just displays the loading sign and stops. But the bet is not accepted. 


![image](https://github.com/user-attachments/assets/f5d8ec6c-fade-4876-916e-56d2255d3875)

Also change the PK 10 Board game labels. Example forward is supposed to be First 5 and Back is supposed to be Last 5 etc.

![image](https://github.com/user-attachments/assets/77c65fc6-ca4b-4ecd-8587-c6e05fee12fa)

Now check the draw result pop up and recent draw history table. They are different. But the right thing is they need to be the same. Also look at the issue numbers for the draw results. While the pop up is on a issue number of 0049, the recent draw history is on 1380. No synchronization at all. 

Also look at 1377 and 1378 issue numbers recent draw history.
- 1377: 9 3 1 8 7 5 10 2 4 6. At the front or last, the system showed last. 
And the logic to this game is add the first 5 numbers, them add the last 5 numbers of the draw.


First 5 = 9+3+1+8+7 = 28. Last 5 = 5+10+2+4+6 = 27. 

So the sum for first 5 is 28 which is greater than the sum for the last 5 which is 27.
And the display is to show which group has the larger number, which in this case is the first 5. So the display should have been first, not last.

- 1378: 9 6 4 3 7 5 8 10 1 2. Again at the front or last, the system showed last.

First 5 = 9+6+4+3+1 = 29. Last 5 = 5+8+10+1+2 = 26.

So the sum for first 5 is 29 which is greater than the sum for the last 5 which is 26.
And the display is to show which group has the larger number, which in this case is the first 5. So the display should have been first, not last.


## 11x5 Board Game

![image](https://github.com/user-attachments/assets/b6006379-efc1-4a62-9160-3a887a925acd)

Again when you click on the bet confirm for PK10 Board game, it does not go through or it is not accepted. It just displays the loading sign and stops. But the bet is not accepted. 









 

