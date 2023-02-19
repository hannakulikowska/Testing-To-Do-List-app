# LIST ACTIONS

### USER STORY
As a user, I should be able to execute various actions on the list.

### WIREFRAME
<img src="https://user-images.githubusercontent.com/80547490/219876967-f6bdfe34-f75d-4789-a1a1-6abb263ce09a.png" width=65% high=65%>

### TEST CASE 02-01<br>
**The Cancel button doesn't work on the actions list.** <br>
:red_circle: **BUG**

| Action                                                                      | Input       | Output                                                                |
|-----------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------|
|1. Cklick the actions button on the list with title "Title 1". <br><img src="https://user-images.githubusercontent.com/80547490/219877476-d11786ea-eed6-47b6-ba2e-8ddd164907e7.png" width=45% high=45%>|             | A list with possible actions was displayed.|
|2. Click the Cancel button on the list with possible actions. <br><img src="https://user-images.githubusercontent.com/80547490/219877485-1c4da857-7b5f-4533-9207-63d626b89181.png" width=45% high=45%>|             | It is impossible to close the list of actions. The Cancel button isn't clickable. --> :red_circle: BUG|