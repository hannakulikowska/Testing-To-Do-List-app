# ADDING A LIST

### USER STORY
As a user I should be able to create a list with a custom title. Number of created lists is not limited. Title length should not exceed 50 characters. 
Application should block possibility to enter more signs. After clicking ‘add’ button I should be able to see the list on the screen. 
The created list should appear on the screen as columns. The button that allows you to add a list should move to the next column in the right direction. 
In the top right corner of the list there should be a button that allows you to delete the list. It should be possible to change the title of created list. 
Within the created list I should be able to create the tasks. It should not be possible to add two lists with the same name.

### WIREFRAME
<img src="https://user-images.githubusercontent.com/80547490/219871118-d9712005-c0a8-4fef-b602-845708cda222.png" width=65% high=65%>

### TEST CASE <br>
:red_circle: **BUG** <br>
**"Add new list" button disappeared.**
<br>

| Action                                                     | Input                  | Output                                                               |
|------------------------------------------------------------|------------------------|----------------------------------------------------------------------|
|1. Cklick on the button "Add new list"                      |                        | "Add new list" button disappeared.                                   |

<br>
<img src="https://user-images.githubusercontent.com/80547490/219898844-6a894014-12a3-4dc1-88db-496fb8fe0749.png" width=85% high=85%>
<br>
<img src="https://user-images.githubusercontent.com/80547490/219898921-90ed9c23-e72f-464f-935f-aeb41f37eb59.png" width=85% high=85%>
<br><br>

### TEST CASE <br>
:red_circle:  **BUG** <br>
**No X button on a pop-up notification.**
<br>

| Action                                                     | Input                  | Output                                                               |
|------------------------------------------------------------|------------------------|----------------------------------------------------------------------|
|1. In the second list I wrote the same title name as in the first list. | List title: Title 1 | The title "Title 1" displayed.                              |
|2. Click "Add" button.                                      |                        |The pop-up notification appeared, that I can not do this. According to the documentation, there should be an X button in the upper right corner of the pop-up, but there is no button.|

<br>
<img src="https://user-images.githubusercontent.com/80547490/219899063-2baf6df1-aca5-427d-93db-3643a26799e5.png" width=85% high=85%>

