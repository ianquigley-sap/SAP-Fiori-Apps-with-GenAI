#  Exercise 5 - Generation and extending an app 


In this exercise you will use your learned skill of generating a Fiori app from a picture and extend this app with the flexible programming model.

Please be aware that you need to complete: [Exercise 0 - Getting Started - Setting up your Development Environment
](../ex0/README.md) and [Exercise 2.1 - Generate an SAP Fiori app from an image](../ex2/README.md)  before you can start Exercise 5.

## Exercise 5.1 Using the other sample images

Navigate to you explorer in the business application stusio and look for the **TravelScenario.png** picture. Double click on the picture to see the preview.
  
![image](ex5img1.png)

The Preview should look like this:

![image](ex5img2.png)

1. Next, navigate to **SAP Fiori** in your Business application menu on the left side.
2. Click on **Choose file (md, txt, jpg)**
3. Select the **TravelScenario.png** from the drop down.

![image](ex5img3.png)

Click **Generate**

![image](ex5img4.png)

Once the app has been successfully generated you should see a **accept project** and **preview** button.
Please click now the **preview** button to open up the app in a preview tab.

![image](ex5img5.png)

The preview of the newly generated app should look like the following picture.

![image](ex5img6.png)

As a next step we want to enhance our Ai generated app. To do this switch back from your **preview** tab in your browser to your **Business Application Studio** tab again. 
Now look for your **staging area** section in the left hand navigation. Now hover your mouse over **STAGING AREA** to reveal the **App Modeler** button. Please press **Start App Modeler**.

![image](ex5img7.png)

Now you can see the page map for our Ai gernerated Travel app. Please check if you can see the **Ai Generator staging area** sign up top. If this is the case, press the edit button on the list report.

![image](ex5img8.png)

As the next step, please find the columns section and press the **add column** button.

![image](ex5img9.png)

Now we want to select *Add Basic Columns** from the drop down menu.

![image](ex5img10.png)

Please open up the dropdown.

![image](ex5img11.png)

In the input field, type in **Business** and set the checkmark on the left hand side radio box.

![image](ex5img12.png)

1. Now click on **String** on the right hand side.
2. Select **Boolean** 

![image](ex5img13.png)

Click Add.

![image](ex5img14.png)

Now we want to add a second column. Please repeat pressing the **add column** button the right hand side again.

![image](ex5img15.png)

Open up the dropdown again.

![image](ex5img16.png)

1. In the input field, type in **Destination** and set the checkmark on the left hand side radio box. This time we want to leave the selection on the right hand side on **String**. 
2. Click on **Add**

![image](ex5img17.png)

In the Columns section you now can see our newly added column (Business & Destination). Now we want to move to the middle on the list. To do so click on the up arrow shown in the picture. 

![image](ex5img18.png)

Once this is done, we want to preview the app again to see the newly created columns in action. Switch to your **preview** tab in your browser and click **1.GO** (Start in German). This will reload the app and reveal the new columns Business and Destination. **(If you dont see the columns after pressing **GO** please try the next step)**

![image](ex5img19.png)


 If you successfully previewed the two new columns (Business and Destination). We can now press the **Use Ai to refine Test Data** Button. 

 ![image](ex5img21.png)

 Click on **Generate**

 ![image](ex5img22.png)

You can now switch back to the preview tab in your browser click **Go** and you should see the Ai refined Test Data.

![image](ex5img23.png)

In case you the reload does not work please switch to your **Business Application Studio** tab and go to your Terminal at the bottom of the page. <br>
Click inside of the terminal field and press:<br>
**control + c (on Mac)**<br>
**STRG + c (on Windwos)**<br>

You should now see<br>**(CDS) - my watch has ended<br>
user: fiori-tools-ai $**

![image](ex5img191.png)

Now you can press the **Preview** button on the left side again. 

![image](ex5img192.png)

If you see that Port 4004 is already in use please see the next step.



You may see a message in the terminal stating that the port is already in use (from previewing our application from exercise 1), click **Return/Enter** to use any other port for preview

![image](ex5img20.png)



As the next step we want to switch the layout of the app to the flexible column layout. <br>
1. To have more room in the business application studio we can now close the preview.<br>
2. Now click on **Page View**

![image](ex5img24.png)

Navigate to the Felxible Column Layout on the right side. Switch from the **Standard Layout** to the **Fexible Column Layout**. For the 2 column layout select **Mid-Expanded**.

![image](ex5img25.png)

As a next step switch to you **Preview** tab again to reload your app with: <br>
**STRG + R (Windows)**<br>
**Command + R (Mac)** <br> **
After this step click on the first item in the list to experience the flexible column layout.

![image](ex5img26.png)

Now click on the first line on the object page

![image](ex5img27.png)

The last step within out Ai Staging Area will be pressing the **Accepting files** button to move the project out of our staging area.

![image](ex5img28.png)

1. Please press **Agree** on the bottom right side of the screen. <br>
2. Please select the first option from the dropdown

![image](ex5img30.png)

## Summary

You've now successfully completed the hands-on workshop. Congratulations!
