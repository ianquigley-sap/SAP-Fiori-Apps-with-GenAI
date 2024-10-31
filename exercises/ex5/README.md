#  Exercise 5 - Generation and extending an app 


In this exercise you will re-use your skills of generating a Fiori app from a picture. This time we will create ai generated mock data and extend the app with the flexible programming model.

Please be aware that you need to complete: [Exercise 0 - Getting Started - Setting up your Development Environment
](../ex0/README.md) and [Exercise 2.1 - Generate an SAP Fiori app from an image](../ex2/README.md)  before you can start Exercise 5.

## Exercise 5.1 Generate your app

Navigate to you explorer in the business application studio and look for the **TravelScenario.png** picture. Double click on the picture to see the preview.
  
![image](ex5img1.png)

The Preview should look like this:

![image](ex5img2.png)

1. Next, navigate to **SAP Fiori** in your Business Application Studio menu on the left side.
2. Click on **Choose file (md, txt, jpg)**
3. Select the **TravelScenario.png** from the drop down.

![image](ex5img3.png)

Click **Generate**

![image](ex5img4.png)

Once the app has been successfully generated you should see a **Accept Project** and **Preview** button.
Please click now the **Preview** button to open up the app in a preview tab.

![image](ex5img5.png)

The preview of the newly generated app should look like the following picture.

![image](ex5img6.png)

## Exercise 5.2 Enhance your app

As a next step we want to enhance our Ai generated app. To do this switch back from your **Preview** tab in your browser to your **Business Application Studio** tab again. 
Now look for your **Staging Area** section in the left hand navigation. Now hover your mouse over **STAGING AREA** to reveal the **App Modeler** button. Please press **Start App Modeler**.

![image](ex5img7.png)

Now you can see the page map for our Ai generated Travel app. Please check if you can see the **Ai Generator staging area** sign up top. If this is the case, press the edit button on the list report.

![image](ex5img8.png)

As the next step, please find the columns section and press the **Add column** button.

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

## Exercise 5.1 Use Ai to refine Test Data 

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

## 5.3 Flexible column layout

As the next step we want to switch the layout of the app to the flexible column layout. <br>
1. To have more room in the business application studio we can now close the preview.<br>
2. Now click on **Page View**

![image](ex5img24.png)

Navigate to the Felxible Column Layout on the right side. Switch from the **Standard Layout** to the **Fexible Column Layout**. For the 2 column layout select **Mid-Expanded**.

![image](ex5img25.png)

As a next step switch to you **Preview** tab again to reload your app with: <br>
**STRG + R (Windows)**<br>
**Command + R (Mac)** <br> 
After this step click on the first item in the list to experience the flexible column layout.

![image](ex5img26.png)

Now click on the first line on the object page

![image](ex5img27.png)

## 5.3 Accepting the project

1. Please press **Accept Project* on the bottom right side of the screen. <br>
2. Please select the first option from the dropdown **ai-images-sample**

You now moved you project out of the staging area.

![image](ex5img28.png)



## 5.3 Using the Flexible Programming Model

Please click one the **SAP Fiori** button in the left hand navigation![](image2.png)


![](image1.png)

Now open the **Open Application Info** ![](image4.png).

![](image3.png)

Click on open the page map that shows application pages and navigation
paths ![](image6.png).

![](image5.png)

Click on **Configure page**![](image8.png).

![](image7.png)

Press the **Delete** button ![](image10.png) to delete Bookings.

![](image9.png)



Next click on the **Add Sections** ![](image14.png) menu item.



![](image13.png)

Click **Actions** and ![](image16.png).

![](image15.png)

1. Click  ![](image18.png).

2. Then click  ![](image19.png).

![](image17.png)

Please fill in the fields shown below

![](image20.png)

Click the **Preview Application** ![](image22.png).

![](image21.png)


Go to the input field up top and put in  **cds watch \--openmyapplication/webapp/index.html?sap-ui-xx-viewCache=false** 

![](image23.png)

Switch to your preview tab in your Browser to see your new Bookings section.

![](image25.png)

Switch back from your preview tab to your Business application studio -> Expand **Bookings**![](image27.png).

![](image26.png)


Click the **Add** ![](image29.png) button menu.

![](image28.png)

Click **Actions** and press![](image31.png).


![](image30.png)

1. Click ![](image33.png) to reveal the dropdown.

2. Choose ![](image34.png).

![](image32.png)

Click Add

![](image35.png)

Click **Add Filter Fields** ![](image14.png).

![](image36.png)

1. Click ![](image38.png) to reveal the dropdown.

2. Check the radiobox for ![](image39.png).
3. Click Add

![](image37.png)

1. Click the ![](image41.png) entry to select it.

2. Find the Live Mode section and click the ![](image42.png)  button opens a dropdown list.

3. Clicking the entry ![](image43.png) selects it.

![](image40.png)

1. Clicking the entry ![](image41.png)
to select it.

2. Find the show **Show Clear Button** section and click the ![](image42.png) button opens a dropdown list.

3. Clicking the entry ![](image43.png) selects it.

![](image44.png)

Click **Edit in source code** ![](image48.png).

![](image47.png)

Please copy the Code snippet below and paste it on the exact position that is shown in the picture:

```
    Capabilities : {
      FilterRestrictions : {
        FilterExpressionRestrictions :
          [{
              Property : 'flightDate',
              AllowedExpressions : 'SingleRange'
          }]
      }
    }
```

![](image49.png)

Switch to your preview tab to see the latest changes to your app.

![](image50.png)

We will now use code completion to add a building block table \
Click **Edit in source code **![](image48.png).



![](image51.png)

Remove this line.

![](image52.png)


Click ** **![](image54.png).

![](image53.png)

add the following code snippet:

```
    <macros:Table id="bookingsTable" metaPath="bookings/@com.sap.vocabularies.UI.v1.LineItem#Travels_bookings" filterBar="FilterBar"/>
```

![](image55.png)

![](image56.png)

Click ** **![](image57.png).

Click .

![](image58.png)




