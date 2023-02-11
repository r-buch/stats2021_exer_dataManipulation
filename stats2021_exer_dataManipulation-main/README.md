# Data Manipulation Exercise

A video demonstration of this assignment is available at: https://youtu.be/RagbMAzVAoY

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Read through the .rtf answer sheet included in this repository. (It's probably best to complete the steps of the assignment using that answer sheet.)
- [ ] Complete the steps of the tutorial.
- [ ] Push your updated file to your GitHub repository.

## Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/gitHubForClassAssignmentsRStudio

## Follow along with this tutorial

### Data Cleaning and Exploration

Data needs to be examined and any problems fixed before analysis can be done. This process of checking data before proceeding with a statistical analysis is often called data cleaning. The steps for data cleaning outlined in this tutorial are discussed in the following videos. You don't need to watch the videos to complete this assignment, but I list them here should you have interest in listening to the original lectures.

* Data screening 1 accuracy (40 min) (optional): https://www.youtube.com/watch?v=_wl5wLEnG7I&t=0s&index=145&list=PLw93TUuxrFAbWrTsvaDsn7Y32l8LHJJXn
* Data screening 2 missing (37 min) (optional): https://www.youtube.com/watch?v=9a3CW8fKA3k&t=0s&index=147&list=PLw93TUuxrFAbWrTsvaDsn7Y32l8LHJJXn
* Data screening 3 outliers (22 min) (optional): https://www.youtube.com/watch?v=zL66kiX5VZg&list=PLw93TUuxrFAbWrTsvaDsn7Y32l8LHJJXn&index=148&t=0s

In statistics, we focus on four areas.

1. Data accuracy
    + make sure data types are correct
    + check for typos
    + check for nonsensical data
    + check categories make sense
    + correct problems if possible or delete
    + reverse code items if needed
    + score instruments if needed
    + keep track of what you do so you can be transparent
2. Missing data
3. outliers
4. Statistical assumptions

### Data Manipulation

This assignment shows some more steps to take to get data ready for analysis in both Jamovi and RStudio.

* Calculating descriptive statistics for variables.
* Using existing variables to compute new variables.
* Recoding variables (reverse scoring)
* Scoring instruments.
* Calculating z-scores.

### RStudio part

* In RStudio open the R markdown file (.Rmd) by clicking on it in the Files pane.
* Complete the steps outlined in the assignment. (See the assignment answer sheet file included in this repository.)
* Create a markdown (.md) document by clicking the Knit button. Make sure the markdown file gets saved in the same folder as the R markdown file so it will get pushed back to your GitHub repository.

### Jamovi part

* Open Jamovi
* Complete the steps outlined in the assignment. (See the assignment answer sheet file included in this repository.)
* The file menu looks like 3 horizontal lines at the top left of the Jamovi window.
* File - Open - Browse
* Navigate to your assignment folder where the files for this assignment are, select the file, and click Open.
* After you complete the steps of the assignment, save a Jamovi file (.omv).
* File - Save As - Browse
* Navigate to your assignment folder where the files for this assignment are and click Save.
* You should now have a .omv file in your assignment folder.
  
  
## Push your updated files to your GitHub repository

* This can be done in RStudio.
  * Be patient as you complete these steps. RStudio can be a bit slow to respond.
  * Click on the Git tab in the top right section of the window.
  * You should see the files in your repository in the window.
  * Click in the checkbox in the Staged column to stage the changes you made.
  * Click on the Commit button. (Just above the Staged, Status, Path labels at the top of the pane.)
  * A new window will open which is titled RStudio: Review Changes.
  * Enter a commit message in the field on the right side of the window and click Commit.
  * Another popup should come up while the commit it made. You can close it when it's done.
  * Click the Push button on the top right of the window.
  * Another popup should come up while the push is done. You can close it when it's done.
  * If you check your GitHub repository, your new files or changes should be there.
* This can be done in VSCode.
  * In VSCode click on the Source Control button.
  * You should see the files that had changes. (Mine has the original file which shows an M next to it and a new file which says checkpoint in the name. You really only need to push the original file, but if you push both it shouldn't hurt anything.)
  * Hover over the changed file. Click the + sign to stage the change.
  * Enter a commit message in the message field and click the checkmark to commit the change.
  * Click on the 3 dots for more actions and select Sync. This will push the updated file to your GitHub repository.
* You can also directly add files to your GitHub repository online.
  * Navigate to your GitHub repository in a browser.
  * Click on the Add File button and select Upload Files. (It's right next to the Code button where you copy the URL for the repository when you clone it.)
  * Drag the files to the window or browse for them.
  * Remember to scroll to the bottom of the window and commit your changes or your file(s) won't be saved.
* Submit the link to your GitHub repository on Canvas.
