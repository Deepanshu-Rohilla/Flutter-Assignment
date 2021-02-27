## Flutter Assignment: Drawing Notes App 
Develop a flutter application with the following specification:
 - The main screen should have a list view containing all the saved drawings.
 - We have a search bar at the top, it filters the list.
 - You should be able to rename the drawing title, add a new drawing or delete any previous drawing (swiping to remove items).

For each drawing when opened
 - It should have a drawing screen to draw/ take signatures (similar to what many delivery companies have).
 - It should have options to clear the screen, save the drawing, rename the file etc.
 - These drawings should be editable.

Note: You should try to save the list so that the list remains even when the app reopens.

![Flutter Assignment 2020](https://user-images.githubusercontent.com/31121102/109359662-ddbfb000-78ab-11eb-84c3-233a669837e5.jpg)

## A very simple Demo of the drawing screen
![signatureOutput](signatureOutput.gif?raw=true "Title")

## Some resources
- **Shared Preferences:** Save data when the app closes. So that you have the drawing list even when you reopen.
  - https://pub.dev/packages/shared_preferences
  - https://stackoverflow.com/questions/62642079/how-do-i-save-data-after-closing-the-flutter-app
- **Drawing Screen** [Flutter: Signature View And Custom Painter Implementation | Drawing App](https://www.youtube.com/watch?v=zu-do2luSAo&ab_channel=mtechviral)
- **Dismissible Widget** for swipe to remove
https://flutter.dev/docs/cookbook/gestures/dismissible

## Optional features
Some of the additional features (bonus) that can be added are:
 - Allow changing the stroke properties like stroke color, stroke type, stroke size etc.
 - Allow sharing of the saved drawing.
 - Reversing of operations i.e the user should be able to "undo" the latest operation.

## Submission Instructions
- Make a new project and make sure to use git right from the beginning.
- Keep committing on every major milestone in the assignment. We will look at the stage-wise commits also (not only the final result).
- Also, add the final apk file in the main root directory of the project
- Add your app description both on README.md and also include screenshots on README.md
- Submit your Github repo link [here](https://forms.gle/P8U2HsXzP25QycTW9).
- If stuck, join the discord channel from [here](https://discord.gg/xwSmtPfk5F) and ask the questions directly


## Deadline
4th March 2021, Thrusday, 11:59 PM
