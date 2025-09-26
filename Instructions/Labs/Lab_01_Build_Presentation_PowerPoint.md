# Lab 01: Build a presentation from start to finish with Copilot in PowerPoint

### Estimated Duration : 45 Minutes

## Lab Overview

In this hands-on lab, you’ll work with Copilot in PowerPoint to create a client-ready presentation for Contoso’s new Chai Tea product line in Latin America. You’ll start by generating slides from an existing Word document, inserting images, and editing text to highlight key features and benefits. Then, you’ll organize the presentation, apply corporate branding standards, and collaborate with your team. Finally, you’ll send the draft presentation to your manager for review to ensure it’s polished and ready for the client meeting.

## Lab Objectives

- Task 1: Create a new presentation based on a Word document
- Task 2: Ask Copilot to help you create an icebreaker slide
- Task 3: Insert an image
- Task 4: Edit the text
- Task 5: Organize the presentation
- Task 6: Send a draft for review (Optional) 

### Lab prerequisites

Throughout this Lab, we'll craft prompts for Microsoft 365 Copilot that reference this file. You should have already uploaded it to OneDrive during the lab setup process, but if you need to download it again, you can do so here and upload in to one drive.

1. In the Lab VM, open a web browser, right click on the following link [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126) then **Copy link** and then paste it on the browser tab to download the word file.

1. Select **Download file**.

    ![](./Media/ms1l1.png)

1. Right click on the following link, [M365 Copilot](https://m365.cloud.microsoft/apps/?auth=2) then **Copy link** and then paste it on the browser tab to navigate to the **M365 Copilot**.

1. Provide the credentials below to login:

   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>

   - **Password:** <inject key="AzureAdUserPassword"></inject>

1. Select **Apps (1)** and then select **Onedrive (2)**.   

    ![](./Media/ms1l2.png)

1. Select **Create or Upload (1)** and then select **File upload (2)**.

    ![](./Media/ms1l3.png)

1. Navigate to **Downloads (1)**, then select **Promotion Plan for Chai Tea in Latin America.docx (2)** and then **Open (3)**.

    ![](./Media/ms1l4.png)

1. Make sure the file uploaded.


### Task 1: Create a new presentation based on a Word document

In this task, you will use Copilot in PowerPoint to generate a draft presentation by uploading the Chai Tea promotion plan Word document and applying a design template.

1. Navigate back to [M365 Copilot](https://m365.cloud.microsoft/apps/?auth=2).

1. Select **Apps (1)** and then select **PowerPoint (2)** to start a new presentation.

    ![](./Media/ms1l5.png)

1. Select **Create a new presentation**.

    ![](./Media/ms1l6.png)

1. Select **Copilot (1)** and then select **Ask Copilot (2)**.  

    ![](./Media/ms1l7.png)

1. Select the **Copilot (1)** icon, then use Copilot to generate a draft presentation using the following prompt **(2)**:

   ```
   Create a presentation about Contoso's Chai Tea based on 
   ```

    ![](./Media/ms1l8.png)

    - In the prompt dialog box, enter a forward slash (**/ (1)**) and select the file **(Promotion Plan for Chai Tea in Latin America.docx) (2)** and then **Send (3)**.
    
      ![](./Media/ms1l9.png)    
    
       >**Note:** If the file doesn't populate in the list, select the plus button then **Attach**. Navigate to **My files** and select the document from your OneDrive folder.

1. Select **Create new presentation**.

    ![](./Media/ms1l10.png)

1. On the **Create a presentation with Copilot**, select **Referense file (1)** then upload the **Promotion Plan for Chai Tea in Latin America.docx (2)** and then select **Chage design (3)**.

    ![](./Media/ms1l11.png)

1. Navigate to **Micrososft 365 (1)**, then select a template **(2)** and then **Select Design (3)**.  

    ![](./Media/ms1l13.png)

1. Select **Send**.

    ![](./Media/ms1l14.png)

1. Copilot displays a presentation outline showing the potential slides and bulleted points to be included on each slide. Review the suggested topic and select **Generate slides** to continue.

    ![](./Media/ms1l15.png)

1. Copilot generates slides and content for each. The presentation may display results in either the **Slide Sorter** or **Normal** view.

1. Review the slides and select **Keep it** to continue.

    ![](./Media/ms1l16.png)

1. While this is a great start, you want to personalize the presentation a bit more for your delivery. Let's see how to improve the content.

### Task 2: Ask Copilot to help you create an icebreaker slide

In this task, you will use Copilot in PowerPoint to brainstorm icebreaker questions for a global audience and generate a slide with an image to engage participants at the start of your presentation.

1. Let's first change the view in PowerPoint, Select **View ()1-> Normal (2)**.

    ![](./Media/ms1l17.png)

1. Return to the **Home (1)** ribbon view.Open the **Copilot (2)** pane 

    ![](./Media/ms1l18.png)

1. Enter the following prompt:

   ```
   Can you help me brainstorm an icebreaker question that would be good for a global audience? Provide three options for me to choose from. 
   ```

    ![](./Media/ms1l19.png)   


1. The first question looks great for our audience, so let's ask Copilot to generate a slide with this question, a corresponding image **(1)**, and to insert this as the first slide in the presentation **(2)**.

1. Enter the following prompt:

   ```
   Use question 1 as the icebreaker, and generate a slide that includes a complementary image. Insert this slide as the first slide in the presentation. 
   ```

    ![](./Media/ms1l20.png)   

    Now, you've got a great way to start a conversation among your meeting participants. Let's look at the presentation now, and see how we can make it even more powerful.

### Task 3: Insert an image

In this task, you will use Copilot in PowerPoint to add or replace images on your slides, either from the corporate library or generated based on your ideas, to better align with your presentation’s content.

1. Let's ask Copilot to insert a diagram on the title slide.

1. Navigate to the title slide that Copilot generated.

    ![](./Media/ms1l21.png)

1. Enter the following prompt in the Copilot pane **(1)**:

   ```
   Replace the image on the Title slide with an image of a person sipping a warm cup of tea. 
   ```

    - Select one image **(2)** and then **insert (3)**

      ![](./Media/ms1l22.png)    

1. Copilot opens the **Designer** feature and creates and displays an image that matches your request. Select one design **(1)**. Delete the original image and edit the new one to best fit the space in the slide **(2)**.

    ![](./Media/ms1l23.png)

### Task 4: Edit the text

In this task, you will use Copilot in PowerPoint to refine and improve the text on your slides, making it more concise, engaging, or tailored to your audience.

1. Navigate to the slide containing the text you may want to edit **(1)**

    - In the Copilot pane, enter the following prompt **(2)**:

      ```
      Edit this text to make it more conversational. 
      ```  
     - Select the text **(3)**
     - Select **+ Add selection (4)** and then **Send (5)**
       
       ![](./Media/ms1l24.png)       

1. Review the suggestions provided by Copilot.

    ![](./Media/ms1l25.png)

1. Copy and paste it onto the slide, and make any necessary adjustments.

    ![](./Media/ms1l26.png)

### Task 5: Organize the presentation

In this task, you will use Copilot in PowerPoint to structure your slides, ensuring a logical flow and clear sequence of topics throughout the presentation.

1. In the Copilot pane, enter the following prompt:

   ```
   Organize this presentation. 
   ```

1. Copilot responds, providing suggestions for each slide. You can select to update the content as you'd like or iterate your prompt to receive additional suggestions. 

1. Ensure that your presentation has a logical sequence and smooth transitions between slides.

### Task 6: Send a draft for review (Optional) 

In this task, you will use Copilot in Outlook to draft and send an email to your manager, sharing your presentation and requesting feedback.

1. Launch Microsoft Outlook from your browser [outlook.office.com](https://outlook.office.com).

1. Select **New mail**.

    ![](./Media/ms1l28.png)

1. Select **Draft with Copilot**.

    ![](./Media/ms1l29.png)

1. Enter the following prompt **(1)** and then **Send (2)**:

   ```
   Draft an email asking for a review of the presentation that I attached to this email. Write the email in a casual tone. 
   ```

    ![](./Media/ms1l30.png)   

1. Review the email draft **(1)**, make any necessary edits, and mention mail ID of intended recipient **(2)** and then **Send (3)**.

    ![](./Media/ms1l31.png)


### Summary

In this lab, you explored how Microsoft 365 Copilot in PowerPoint can help build a professional presentation from start to finish. You created a new presentation from a Word document, added an icebreaker slide, inserted and edited images, refined text, and organized content to ensure clear flow. Finally, you applied corporate branding standards and shared the draft for review, experiencing how Copilot streamlines collaboration and enhances presentation design.

### You have successfully completed the Hands-on Lab!
