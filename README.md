# Art History Image Practice
blah blah blah

## Starting Fresh
### Setting up a GitHub Repository
1. Sign in to an existing GitHub account or [create a new account](https://github.com/signup). 
2. Click your user icon in the top right. Then select Your respositories -> New.
3. Ensure that the owner of the repository matches your Github username.
4. Give the respository a name. The name of the respository will become part of the URL of the final webpage. It should not contain any spaces (use hypens instead) or any special characters. 
5. Ensure that the visibility of the respository is set to Public.
6. The default options are fine for the remaining settings 
    - "Add a README file" is unchecked
    - .gitignore template is set to None
    - License is set to None
7. Click "Create repository".

### Populating the Repository 
1. Go to the [arth-pair-practice respository](https://github.com/nicolekaff/arth-pair-practice)
2. Click the green **Code** button at the top and select **Download ZIP**.
3. Unzip the downloaded file **arth-pair-practice-main.zip**.
4. Enter the unzipped **arth-pair-practice-main** folder. You should see a single folder inside that is also named **arth-pair-practice-main**. Enter this folder too and then open the file **code.js**. *Note: You can open **code.js** in any text editor, including Notepad on Windows (right click -> Open with -> Notepad) or TextEdit on Mac (right click -> Open with -> TextEdit)* 
6. Update lines 4-7 of **code.js** by replacing the text within quotations with your information (keep the quotations and the semicolon). The USER_NAME should match your Github account username, REPO_NAME should be the name of the Github respository that you created. COURSE should be the course code for which the webpage is intended for. See below for an example where the Github user name is nicolekaff, the repository name is arth-pair-practice, and the course code is ARTH200. 
```javascript
// Constants - update these as needed!
const USER_NAME = "nicolekaff";
const REPO_NAME = "arth-pair-practice";
const COURSE = "ARTH200";
```
7. Save **code.js** and close the file. 
8. Enter the **data** folder and then copy and paste your initial images into the **imgs** sub-folder. 
9. Enter the **meta** sub-folder. Copy and paste the initial metadata files into the corresponding **architecture** and **art** folders. See the **Formatting the Data** section below for instructions on how the data should be formatted. 
10. Return to your newly created empty Github respository. With the **Code** tab selected, click **upload an existing file** at the top under **Quick setup**. 
11. Go to the innermost **arth-pair-practice-main** folder in your file explorer and select all of the files/subfolders. Click and drag these into the area labeled **Drag fies here to add them to your repository.** *Note: It is important that the click-and-drag method is used rather than clicking "choose your files* and uploading from there. Clicking and dragging ensures that the all files in the data subfolder will be properly uploaded.
12. At the bottom, ensure that **Commit directly to the main branch** is selected and then click **Commit changes**. 

### Making the Webpage Live
1. Click the **Settings** tab of your repository.
2. Click **Pages** on the left sidebar under **Code and automation**.
3. Under **Source** it should say that GitHub pages is currently disabled. In the dropdown menu change the selected option from **None** to **main** and then hit **Save**. 
4. A message should appear telling you that your site is ready to be published. Clicking the link should take you to the live webpage. *Note: It may take a few minutes for the webpage to show up, as GitHub needs time to build, deploy, and check the page status. Refreshing the page should render it when it's ready.*

## Formatting the Data

## Updating the Page
Use the following steps to add new images to the webpage:
1. On the GitHub repository, enter the **data** folder and then the **imgs** folder. 
2. In the upper right, select **Add file -> Upload files**.
3. Drag and drop the new images or select **choose your files** and upload them from there.
4. At the bottom, ensure that **Commit directly to the main branch** is selected and then click **Commit changes**. 

Use the following steps to add the corresponding data files for the new images:
1. On the GitHub repository, enter the **data** folder and then the **meta** folder. 
2. Enter the **architecture** folder.
3. In the upper right, select **Add file -> Upload files**.
4. Drag and drop the new data files for all architecture pieces or select **choose your files** and upload them from there.
5. At the bottom, ensure that **Commit directly to the main branch** is selected and then click **Commit changes**. 
6. Go back to the **meta** folder and then enter the **art** folder.
7. Repeat steps 3-5 for the artwork data pieces. 

## Credit
