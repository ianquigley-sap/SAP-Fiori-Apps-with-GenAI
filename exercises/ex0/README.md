# Getting Started - Setting up your Development Environment

As a particpant of the hands-on, you should already be setup with access to the SAP Business Application Studio landscape below which you can use as your development environment.

## Accessing SAP Business Application Studio

Navigate to https://lcapteched.eu10.build.cloud.sap/lobby

<span style="color:red">**NOTE:  BAS AI is only supported on Chrome.  Please ensure you use the Chrome Browser.** </span>


## Accessing the Dev Space Manager

On the SAP Build landing page, click button **Switch Product** in the top right corner and select **Dev Space Manager**.
![Access Dev Space Manager](ex0img0.png)
## Creating the Development Space

<span style="color:red">Your dev space has been precreated for the hands-on session.
If your dev space manager shows FioriAppsGenAI, continue directly with step </span> [Opening the Development Space](#opening-the-development-space)

If the **Welcome to** landing page is shown instead, you have to create a new dev space as follows.


Click on the button **Create Dev Space**.

![Create Dev Space](ex0img1.png)

Enter a name for your development space and select application profile **Full Stack Cloud Application**.

![Select Profile](ex0img2.png)

In the lower right corner of the page press button **Create Dev Space**.

![Confirm](ex0img3.png)

## Opening the Development Space

Make sure your development space has status running. If stopped, click the start button. 
![Restart Dev Space](ex0img4a.png)
Once running, click on the development space name to open it.  This can take some time.

![Enter Dev Space](ex0img4.png)

Click **OK** in the popup window to accept the tracking settings in the newly created dev space.

![image](ex0img5.png)


## Enable Generative AI features with SAP Fiori Tools

Next you will need to enable the feature toggle to allow for generative AI with SAP Fiori tools.  Please follow these steps:

1. Click on the three lines icon in the top left hand side of the window.
2. Select **File**
3. Select **Preferences**
4. Then select **Settings**

![image](ex0img6.png)


Click on the file icon in the top right of the screen to enable the settings file to appear.

![image](ex0img7.png)

You will be presented with a blank file apart from 2 curly braces:

![image](ex0img8.png)

Between the curly braces, enter the text:

```JSON
"sap.ux.help.testBetaFeatures.enableFioriAI": "165a0e31-35ea-4bee-8d47-b8593435a82d"
```

Your file should look as follows:

![image](ex0img9.png)

Click on the `x` to close the settings window.

## Open your project folder

Open the explorer icon from the left hand side:

![image](ex0img10.png)

And select **Open Folder** button

![image](ex0img11.png)

Select the **Projects** folder from the drop down

![image](ex0img12.png)

Click **OK** and your window will reload

![image](ex0img13.png)

## Summary

With the setup procedure done, you now have completed:

- Access to SAP Business Application Studio
- Creation of your development space
- Enabling of the SAP Fiori tools AI features

Continue to - [Exercise 1 - Generate an SAP Fiori app from business requirements](../ex1/README.md)