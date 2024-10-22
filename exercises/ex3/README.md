#  Exercise 3 - Generate an SAP Fiori app using images and text


In this exercise, we will create an **SAP Fiori** application using a document that contains both text and images, so that the required application can be best described.


## Exercise 3.1 Uploading the business requirement document with images

In the explorer in SAP Business Application Studio, expand the **classical_transaction** folder and right click on the **multi_image_old_ui.md** file (1).  Then click on the **Open Preview** link (2).

![image](ex3img1.png)

You should then see a document that includes a mixture of text and images.  This document contains images from a classic transaction app and details what each of the sections in the object page should contain with a mixture of screenshots and text.

![image](ex3img2.png)

Similar to the previous exercises, click on the SAP Fiori tools icon to open the panel with the AI Automated Generator displayed (you can close the **Application Modeler** and **Information** sections):

![image](ex3img3.png)

Click on the **Load file** link

![image](ex3img4.png)

Click into the **classical_transaction** folder

![image](ex3img5.png)

Select the **multi_image_old_ui.md** file

![image](ex3img6.png)

The text of the file will be populated into the text box.  Click **Generate** to start generating your application.  This will take some time.

![image](ex3img7.png)

## Exercise 3.2 Reviewing the generate application from a business requirement document with images

After generation completes, click on the **Preview** button to launch a preview of the generated application.  

![image](ex3img8.png)

You may see a message in the terminal stating that the port is already in use (from previewing our application from the last exercise), click **Return/Enter** to use any other port for preview

![image](ex3img9.png)

A new browser tab should open with the generated application. 
![image](ex3img10.png)

Select an item from the list and the object page should display with the details:

![image](ex3img11.png)

Navigate back to the tab with SAP Business Application Studio, and click **Accept** to include this project into your workspace

![image](ex3img12-2.png)

Click on the **Explorer** icon and you should have another new folder for the project, this time entitled **ai-created-cap-1**

![image](ex3img13.png)

## Summary

In this exercise you have seen how the Fiori AI generator can use both text and images to create detailed **SAP Fiori** apps.

Continue to - [Exercise 4 - Other sample images for Generation](../ex4/README.md)
