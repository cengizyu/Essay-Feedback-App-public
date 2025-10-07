# How to use the tool

## Prerequisites 
1. All files should be in Microsoft Word (.docx) format. Otherwise the program might not respond.
2. I suggest sharing a Google Drive folder with students and asking them to upload their work on that Google Drive folder. Folders such as "Task 1 - Draft 1" can be created and shared with the students. 
3. Once the students upload their essays, right click on the Google Drive folder (e.g. ""Task 1 - Draft 1"") and click on "Download".
4. Google Drive will download a .zip or .rar file. Extract the folder by dragging and dropping them on a screen of your choice. (For example, I have a folder named "P3.06 Essays" and I can drop the folder inside this one.
5. Once the folder is extracted, everything is ready. 

## 1. Downloading the app
Download the app by clicking on the file under "releases" on the right hand side. 

## 2. Starting the app
Start the app by double clicking on the EssayFeedbackApp.exe 

## 3. Initial setup
Before you can use the program, a code must be entered. Please contact the author to receive your code and instructions. 

## 4. Tabs
This is the main window. 
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/bcd270c2-c78a-4b78-9535-08611c35641f" />

- "Run" tab is our main workplace. 
- "Prompts" tab is used to personalize the prompts. Changes here should be made with the author in order to produce the desired outputs. If any changes are made to the prompts, the user should click on "save override" to save their changes. Before you personalize your prompts, it is always a good idea to copy and paste what is already on the "prompt" screen. Parts under "Output Format", "Anchoring Rules" and "JSON policy" should not be changed.
- "Rules (YAML)" tab is used to personalize the feedback comprehensiveness. Changes here should be made with the author in order to produce the desired outputs. If any changes are made to the prompts, the user should click on "save override" to save their changes.  Before you personalize your YAML, it is always a good idea to copy and paste what is already on the "YAML" screen. 
- "About" tab contains all the relevant information regarding the tool.

## 5. Workflow 1 - Personalizing prompts
- "Prompts" tab is used to personalize the prompts.
- Changes here should be made with the author in order to produce the desired outputs. 
- Parts under "Output Format", "Anchoring Rules" and "JSON policy" should not be changed.
- If any changes are made to the prompts, the user should click on "save override" to save their changes. 
- Before you personalize your prompts, it is always a good idea to copy and paste what is already on the "prompt" screen.
- If needed, the default prompt can be found here /defaultprompt.txt. You can copy and paste it into the "Prompts" screen and click on save override.
## 5. Workflow 2 - Personalizing YAML
- YAML decides the number of minimum output that the program needs to produce each time.
- Changes here should be made with the author in order to produce the desired outputs. 
- This screen can be used if the user would like to increase the feedback generated for one area, or would like to stop the tool from generating feedback for a specific area, i.e. grammar, vocabulary, organization or content.
- When personalizing, the user can either can click on "edit in place" and "save" after making changes or can upload a different YAML document.
- If needed, the default YAML can be found here /defaultprompt.txt. The structure should not be changed, e.g. each YAML document should have a "profile".
- If this screen is left empty, the program switches to in-built YAML.

## 5. Workflow 3 - Uploading the essays and generating outputs - Single files
- To provide feedback for one essay only "Single file" option should be used.
- For "Input docx", click on "browse" and find the file.
- Choose an AI model.
- If any YAML profiles are loaded, you can see them under "Profile".
- Click on "Generate margin comments"
- The program will run and generate the comments for the essay and the output folder will be named "DocumentName_feedback.docx" and will be placed in the same folder as the original file.
- The program will open up the word document once it finishes generating feedback.

## 5. Workflow 4 - Uploading the essays and generating outputs - Multiple files
- To provide feedback for one essay only "Single file" option should be used.
- For input folder, click on "browse" and find the folder with essays.
- For output folder, choose where you want the outputs to be created. You can choose the same folder as input folder, or you can create a new folder named "Feedbacks" and choose that. 
- Choose an AI model.
- If any YAML profiles are loaded, you can see them under "Profile".
- Click on "Run Batch"
- The program will run and generate the comments for the essays and the place them in your selected output folder.
- Essays with feedback will have the name "DocumentName_feedback.docx"

## 5. Workflow 5 - Reviewing comments and sending the essays back to students
- The program works better with a Google Drive interface.
- I recommend uploading the student essays back to a the students' Google Drive folder.
- Now, you can review the comments generated by AI much easier. You can add new comments by selecting a text, right clicking on them and clicking on "add comment". 
