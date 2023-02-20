# ADDING A LIST
**Testing the function of adding lists.**

### USER STORY
As a user I should be able to create a list with a custom title. Number of created lists is not limited. Title length should not exceed 50 characters. 
Application should block possibility to enter more signs. After clicking ‘add’ button I should be able to see the list on the screen. 
The created list should appear on the screen as columns. The button that allows you to add a list should move to the next column in the right direction. 
In the top right corner of the list there should be a button that allows you to delete the list. It should be possible to change the title of created list. 
Within the created list I should be able to create the tasks. It should not be possible to add two lists with the same name.

### WIREFRAME
<img src="https://user-images.githubusercontent.com/80547490/219871118-d9712005-c0a8-4fef-b602-845708cda222.png" width=65% high=65%>



### TEST CASE ID: 01-01 <br>
**TEST RESULT: FAIL** `🔴 BUG` <br> 
**The button for adding a new list has disappeared** <br>

**Execution preconditions:**
1. Launch the application (Test Case 01-00).

**Test Data:**<br><br>
None.

**Step Details:**
1. Cklick the add button for adding a new list (Screenshot 1). <br>

**Expected Results:**
A new list will be created.

**Actual Results:**
The add button has disappeared (Screenshot 2). <br><br>

**Attachments:** <br><br>
<img src="https://user-images.githubusercontent.com/80547490/219898844-6a894014-12a3-4dc1-88db-496fb8fe0749.png" width=10% high=10%> *Screenshot 1* <br> 
<img src="https://user-images.githubusercontent.com/80547490/219898921-90ed9c23-e72f-464f-935f-aeb41f37eb59.png" width=10% high=10%> *Screenshot 2*
<br><br><br>


**THE BUG (TC 01-01) WAS FIXED** <br>

### TEST CASE ID: 01-02 <br>
**RETESTING** <br>
**TEST RESULT: PASS** <br>
**"Add new list" button works correctly** <br>

**Execution preconditions:**
1. Launch the application (Test Case 01-00).

**Test Data:**<br><br>
None.

**Step Details:**
1. Cklick the add button for adding a new list (Screenshot 1). <br>

**Expected Results:**
A new list will be created.

**Actual Results:**
A new list was added. (Screenshot 2). <br><br>

**Attachments:** <br><br>
<img src="https://user-images.githubusercontent.com/80547490/219898844-6a894014-12a3-4dc1-88db-496fb8fe0749.png" width=10% high=10%> *Screenshot 1* <br>
<img src="https://user-images.githubusercontent.com/80547490/220021908-3d8c52fd-9278-4b6b-9351-e19bbdab6f13.png" width=10% high=10%> *Screenshot 2*
<br><br><br>



### TEST CASE ID: 01-03 <br>
**TEST RESULT: FAIL** `🔴 BUG` <br>
**The title box is not automatically cleared after creating a new list**

**Execution preconditions:**
1. Launch the application (TC 01-00).
2. Add a new list (TC 01-02).

**Test Data:**<br><br>
List title: Title 1 <br>

**Step Details:**
1. Write the title name in the list (Screenshot 1). <br>
2. Click add button to confirm the list title.

**Expected Results:**
The created list will be given a title name and next list will automatically appear without any title or there will be a button for adding next list.

**Actual Results:**
The list is titled. A new list was automatically added, but the title box is not empty. (Screenshot 2). <br><br>

**Attachments:** <br><br>
<img src="https://user-images.githubusercontent.com/80547490/219943598-9b703670-6690-4ee6-89fc-462f91db1f2c.png" width=10% high=10%> *Screenshot 1* <br>
<img src="https://user-images.githubusercontent.com/80547490/219944566-e72cb299-329e-4d51-ab53-242043126f31.png" width=10% high=10%> *Screenshot 2*
<br><br><br>



### TEST CASE ID: 01-04 <br>
**Verification of impossibility to add two lists with the same name**
**TEST RESULT: PASS <br>

**Execution preconditions:**
1. Launch the application (TC 01-00).
2. Add a new list (TC 01-02).
3. Add a title of the list (TC 01-03).

**Test Data:**<br><br>
List title: Title 1. <br>

**Step Details:**
1. In the second list, write the same title as in the first list.<br>
2. Click the add button in the second list.

**Expected Result:**
A pop-up notification will appear after trying to add a list with the same name.

**Actual Result:**
The pop-up notification appeared that says "There is already a list with the same name".<br><br>

**Attachments:** <br><br>
None.
<br><br><br>



### TEST CASE ID: 01-05 <br>
**TEST RESULT: FAIL** `🔴 BUG` <br>
**Pop-up notification don't have X button**

**Execution preconditions:**
1. Launch the application (TC 01-00).
2. Add a new list (TC 01-02).
3. Add a title of the first list (TC 01-03).
4. Add the same title for the second list as in the first list (TC 01-04).

**Test Data:**<br><br>
None.<br>

**Step Details:**
1. Click the X button to close pop-up notification (Screenshot 1).

**Expected Results:**
A pop-up notification will appear after trying to add a list with the same title name as previous.  

**Actual Results:**
According to the documentation, there should be an X button in the upper right corner of the pop-up, but there is **no X button**. (Screenshot 2).<br>

**Attachments:** <br><br>
<img src="https://user-images.githubusercontent.com/80547490/219899063-2baf6df1-aca5-427d-93db-3643a26799e5.png" width=10% high=10%> *Screenshot 1*
<br><br><br>
