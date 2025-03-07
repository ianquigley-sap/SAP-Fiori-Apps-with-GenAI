#  Exercise 3 - Generate an SAP Fiori app using images and text


In this exercise, we will create an **SAP Fiori** application using a document that contains both text and images, so that the required application can be best described.


## Exercise 3.1 Uploading the business requirement document with images

In the explorer in SAP Business Application Studio, expand the **classical_transaction** folder and right click on the **multi_image_old_ui.md** file (1).  Then click on the **Open Preview** link (2).

![image](ex3img1.png)

You should then see a document that includes a mixture of text and images.  This document contains images from a classic transaction app and details what each of the sections in the object page should contain with a mixture of screenshots and text.

![image](ex3img2.png)

Similar to the previous exercises, click on the SAP Fiori tools icon to open the panel with the AI Project Accelerator displayed (you can close the **Application Modeler** and **Information** sections):

![image](ex3img3.png)

Click on the **Load file** link

![image](ex3img4.png)

Click into the **classical_transaction** folder

![image](ex3img5.png)

Select the **multi_image_old_ui.md** file

![image](ex3img6.png)

The text of the file will be populated into the text box.  Click **Generate** to start generating your application.  This will take some time.

![image](ex3img7.png)

## Exercise 3.2 Previewing the generated application from a business requirement document with images

After generation completes, a dropdown will appear with a selection. Please choose the ai-image-samples folder.

![image](ex3img8.png)

Click on the **Explore** icon and you should have another new folder for the project, this time entitled **ai-created-cap-1**. Open the context menu with **right-click** and select preview application to launch a preview of the generated application.

![image](ex3img9.png)

You may see a message in the terminal stating that the port is already in use (from previewing our application from the last exercise), Navigate to the terminal and open the one you used for the last preview and use **CTRL + C** to stop it from running. Then try previewing your application again.

![image](ex3img10.png)

A new browser tab should open with the generated application. <br>

![image](ex3img11.png)

Select an item from the list and the object page should display with the details:

![image](ex3img12.png)

## Summary

In this exercise you have seen how the Fiori AI generator can use both text and images to create detailed **SAP Fiori** apps.

Continue to - [Exercise 4 - Other sample images for Generation](../ex4/README.md)
