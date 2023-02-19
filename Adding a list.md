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
**The button for adding a new list has disappeared.** <br>

**Execution preconditions:**
1. Open the application (Test Case 01-00).

**Test Data:**
No data.

**Step Details:**
1. Cklick the add button for adding a new list (Screenshot 1). <br>

**Expected Results:**<br><br>
A new list will be created.

**Actual Results:**<br><br>
The add button has disappeared (Screenshot 2). <br><br>

**Attachments:** <br><br>
<img src="https://user-images.githubusercontent.com/80547490/219898844-6a894014-12a3-4dc1-88db-496fb8fe0749.png" width=10% high=10%> *Screenshot 1* <br> 
<img src="https://user-images.githubusercontent.com/80547490/219898921-90ed9c23-e72f-464f-935f-aeb41f37eb59.png" width=10% high=10%> *Screenshot 2*
<br><br><br>


**THE BUG WAS FIXED.** <br>
**RETESTING.** 

### TEST CASE ID: 01-02 <br>
**TEST RESULT: PASS** <br>
**"Add new list" button works correctly.** <br>

| Action                                      | Input                  | Output                                                               |
|---------------------------------------------|------------------------|----------------------------------------------------------------------|
|1. Cklick "Add new list" button. <br><img src="https://user-images.githubusercontent.com/80547490/219898844-6a894014-12a3-4dc1-88db-496fb8fe0749.png" width=45% high=45%>|     | "Add new list" button works correctly. A new list was added. <br> <img src="https://user-images.githubusercontent.com/80547490/219969215-ca736ec5-8f42-48cf-bf96-96f432ac756d.png" width=45% high=45%>|

### TEST CASE ID: 01-03 <br>

TEST RESULT: :red_circle: **BUG** <br>
**No X button on a pop-up notification.** <br>


| Action                                                     | Input                  | Output                                                               |
|------------------------------------------------------------|------------------------|----------------------------------------------------------------------|
|1. Cklick "Add new list" button. <br><img src="https://user-images.githubusercontent.com/80547490/219898844-6a894014-12a3-4dc1-88db-496fb8fe0749.png" width=45% high=45%>|        |A list appeared.<br><img src="https://user-images.githubusercontent.com/80547490/219943486-52318be7-c4d3-49d7-8f11-b27b40732063.png" width=45% high=45%>|
|2. Write title name in the list. |List title: Title 1     |Entered text displayed in the title field. <br><img src="https://user-images.githubusercontent.com/80547490/219943598-9b703670-6690-4ee6-89fc-462f91db1f2c.png" width=45% high=45%>|
|3. Click "Add" button to add the list. |        |The first list has been given the title. And the second list appeared next to. <br>In the second list, the title name is already written in the field, the same as in the first list -> 🔴 BUG. <br><img src="https://user-images.githubusercontent.com/80547490/219944566-e72cb299-329e-4d51-ab53-242043126f31.png" width=45% high=45%>|


|4. In the second list, leave the existing title "Title 1" in the field and click the "Add" button.|    |The pop-up notification appeared, that there is already a list with the same name. According to the documentation, there should be an X button in the upper right corner of the pop-up, but there is no button. -> 🔴 BUG. <br><img src="https://user-images.githubusercontent.com/80547490/219899063-2baf6df1-aca5-427d-93db-3643a26799e5.png" width=45% high=45%>|
|5. Close the pop-up by clicking outside of the window.|       |The pop-up disappeared.|
|6. 


Title length should not exceed 50 characters - 0, 50, 51 dwu. Application should block possibility to enter more signs.
Number of created lists is not limited.






|6. Delete the list with the title "Title 1" by cklicking X button in the top right corner of the list.|      |The X button doesn't work. It is impossible to close the list. -> 🔴 BUG. <br><img src="https://user-images.githubusercontent.com/80547490/219949028-69cd50ce-9aed-46c9-8d67-54fbf4c11c32.png" width=45% high=45%>|
|7. Change the title of created list with the title "Title 1" by clicking the Edit button in the top right corner of the list.|      |The Edit button doesn't work. It is impossible to edit the list title. -> 🔴 BUG <br><img src="https://user-images.githubusercontent.com/80547490/219949715-f7769704-e6f1-41a5-8005-3892fa935de4.png" width=45% high=45%>|


|8. The button that allows you to add a list should move to the next column in the right direction. 

|Within the created list I should be able to create the tasks.
