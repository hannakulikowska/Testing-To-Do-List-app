# ADDING A LIST

### USER STORY
As a user I should be able to create a list with a custom title. Number of created lists is not limited. Title length should not exceed 50 characters. 
Application should block possibility to enter more signs. After clicking ‘add’ button I should be able to see the list on the screen. 
The created list should appear on the screen as columns. The button that allows you to add a list should move to the next column in the right direction. 
In the top right corner of the list there should be a button that allows you to delete the list. It should be possible to change the title of created list. 
Within the created list I should be able to create the tasks. It should not be possible to add two lists with the same name.

### WIREFRAME
<img src="https://user-images.githubusercontent.com/80547490/219871118-d9712005-c0a8-4fef-b602-845708cda222.png" width=65% high=65%>


# TEST SUITE ID: 01


### TEST CASE ID: 01-01 <br>
**SUMMARY:** ADDING THE FIRST LIST <br>
**STATUS:** `BLOCKED 🔴` <br> 

**Execution preconditions:**
1. Launch the application.

**Test Data:**<br> 
Title: Title 1. <br>

**Steps:**
2. Cklick add button for adding the first list.
2. Write the title in the title field.
3. Click add button to confirm the title.

**Expected Result:** The first list will be created. <br>




### TEST CASE ID: 01-01 <br>
**SUMMARY:** ADDING THE FIRST LIST <br>
**RETESTING** <br>
**TEST RESULT:** `PASSED 🟢` <br>

**Execution preconditions:**
1. Launch the application.

**Test Data:**<br> 
Title: Title 1. <br>

**Steps:**
2. Cklick add button for adding the first list.
2. Write the title in the title field.
3. Click add button to confirm the title.

**Expected Result:** The first list will be created. <br>




### TEST CASE ID: 01-02 <br>
**SUMMARY:** ADDING TWO LISTS WITH THE SAME NAME
**TEST RESULT:** `FAILED 🔴` <br>

**Preconditions:**
1. Launch the application.
2. Add the first list.

**Test Data:**<br><br>
List title: Title 1 <br>

**Step Details:**
1. Write the same title in the second list as in the first list. <br>
2. Click add button to confirm the title.

**Postconditions:** 
Close the pop-up notification by clicking X button.

**Expected Result:**
A pop-up notification will appear after an unsuccessful attempt to add a list with the same name.

