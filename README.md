## Analysis of green initiative stock from 2017 and 2018 

![image](https://user-images.githubusercontent.com/93869894/143667274-c55fe5ca-5c24-47e0-a6f2-a6c681915669.png)


The purpose of the analysis was to assist Steve with calculations and predict which stocks would be ideal for his parents to invest in.

These calculations we're based on stock information on 12 companies that are pursuing green initiatives to better the environment for the future.  The analysis had three variables that we were tracking 1) ticker, 2) Total Daily Volume, and 3) Return.  Once the variables were determined, and the data set established, the structure of code needed to be defined to ensure that the corrct information was being pulled from the data set for an accrate annalysis.  we started with some of the basic formating that needed to be completed like formating the output sheet, create header rows and initialize array of all tickers.

After that has been established, the needed to create a ticker index, ![image](https://user-images.githubusercontent.com/93869894/143667408-13a8a6ae-df01-438a-9f63-1ac8663e2cab.png), followed by the output arrays, ![image](https://user-images.githubusercontent.com/93869894/143667487-81980d4f-b5a0-427e-9dd1-01cadc3695e9.png), and the tickerVolumes set to zero ![image](https://user-images.githubusercontent.com/93869894/143667682-16481711-1ad8-4438-b34f-9574bf698bbd.png).  We needed to be able increase volume, identify the first and last row, as well as increase the tickerIndex for the tickers ![image](https://user-images.githubusercontent.com/93869894/143667780-e28193ac-a519-405e-9a26-df5ece847a13.png), ![image](https://user-images.githubusercontent.com/93869894/143667788-286b5d10-bc02-4ca1-ad3b-f7f45d2f0ea3.png), ![image](https://user-images.githubusercontent.com/93869894/143667803-88f93ab2-c884-4ed4-8e15-5328eb43d854.png), ![image](https://user-images.githubusercontent.com/93869894/143667816-5c4c2b4d-b589-4635-8d14-46f6727aac81.png).  Finally we needed some way to display the results of the analysis identifying the Ticker, Total Daily Volume, and Return ![image](https://user-images.githubusercontent.com/93869894/143667880-d92e71f3-9b61-408e-b781-5f471e8cebc2.png).  

As need in the snapshots of the analysis results below, you can determine that there was a decrease in total daily volume in 2018 compared to 2017.  However there are two stocks that increased daily volume in both years ENPH with a 129.5% return in 2017 and a strong 81.9% in 2018.  The other stock that performed well in comparison in both years was RUN with 5.5% return in 2017 and an increaing return of 84.0% in 2018.

![image](https://user-images.githubusercontent.com/93869894/143668047-83a4eaa2-bd13-40ac-9daf-a397e62c17ee.png)
![image](https://user-images.githubusercontent.com/93869894/143668061-5e3e4148-891e-4951-b165-2147b5bc2a40.png)

Also you can tell from the images above that time it took for the refactored subrutine only took a fraction of a scond to determine the outcomes.  The original subrutine calculated the outcomes as follows 2018 .8828125 of a second and 2017 in .828125 of a second; while both of these times are quick, the refactored subrutine was able to calaulate in .74219 of a second faster for 2018 and .828125 faster for 2017.

There are pros and cons to consider if you are going to consider refactor existing code. A copule things to consider delivery deadline, cost, release date.  If you do not have time to review the refactored code for bug fixes, test enhancements, or have a peer review, then it would be a good idea to hold off if possible.

Having the time to work on the refactoring of the original code for this stock analysis was benefitial as it allowed for some bug fixes and clean up some older code that might have been used.  The added benefit of inproved process speed will be beneficial for Steven to use on his other clients to better assist in their long term financial needs.
