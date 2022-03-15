# Hello Class

### Description

Hello Class is a way for students to say "Hello" to their classmates and me. Doing so will help them solidify what they've learned in the guided project for the day.

After completing this project you will be able to:

* Create new scenes inside of storyboard
* Add new elements to those scenes
* Edit properties of UIView objects
* Create and use segues to navigate different views
* Use UINavigationController
* Test an app using simulator

## Guide

### Main Screen

Build a UIViewController that contains a photo, your name and a UIButton that will segue to the Interests Screen where they can learn more about you.

1. Open the only UIViewController scene in Main.storyboard
2. Use UIImageView, UILabels, and UIButtons to create the view described above.
3. Make sure everything in constrained correctly. Test the view to confirm it works on multiple simulators.

<details>
  <summary>Image Hint</summary>

  To load a UIImage you will need to put that image inside of the Assets area in Xcode.

</details>

### Interests Screen

Build another UIViewController. This time, it will contain a StackView of buttons. Make each button's title a interest you have. You should have between 5-10 buttons.

1. Create a new UIViewController inside of Main.storyboard. Don't forget to create a new file/class.
2. Use a StackView and UIButtons to create the view described above.
3. Create a segue from the Main Screen's UIButton to the Interest Screen. Use the "Show" segue.
4. Embed the Main Screen view inside a navigation controller.
5. Create a segue from the Main Screen's UIButton to the Interest Screen. Use the "Show" segue.
6. Make sure everything in constrained correctly. Test the view to confirm it works on multiple simulators.

### Interest Detail Screen

1. Create a new UIViewController inside of Main.storyboard. Don't forget to create a new file/class. You will need to do this for each interest you have.
2. Each Interest from the previous Interests Screen should lead to another view with more details about that interest. Use show segues.
3. Design these however you like. The only requirement is to have more information about that interest and how that relates to you.
4. You should be able to go back to the interests screen to click on other interests.

### Tests

* All screens work on multiple phone sizes
* UIViewController files for each ViewController inside of Main.storyboard
* Segues are Show segues
* All views share one NavigationController
* Other specs can be read from the guide above

### Stretch Goals

Do NOT read these until after you finish the project. Do not focus on these at all until everythig else is complete.

* Add Background colors to each view
* Style the Labels and Buttons to look different then the default
* Install the app on a real iPhone device
* Have all the detail screens share one ViewController inside storyboard that changes the information dynamically depending on which interest you click on

## License / Copyright

© Bradley Gilmore 2022. Unauthorized use and/or duplication of this material without express and written permission from Bradley Gilmore is strictly prohibited.
