# Hello Class

### Description

Hello Class is a way for students to say "Hello" to their classmates and I. Doing so will help them solidify what they've learned in the guided project for the day.

After completing this project you will be able to:

* Create new scenes inside of storyboard
* Add new elements to those scenes
* Edit properties of UIView objects
* Create and use segues to navigate different views
* Use UINavigationController
* Test an app using simulator

## Guide

### Getting Started

1. Fork this project by clicking the fork icon on GitHub.
2. Clone your forked version of the project down using Git. 

Note: If you need a refresher on this checkout the GitHub overview video in your Precourse work.

3. Create a new project, name it Hello-Class, and save it inside of your newly cloned folder.

### Main Screen

Build a UIViewController that contains a photo, your name and a UIButton that will segue to the Interests Screen where they can learn more about you.

1. Open Main.storyboard and locate the only UIViewController scene.
2. Use UIImageView, UILabels, and UIButtons to create the view described above.
3. Setup constraints for whatever elements you added in step 2.
4. Make sure everything is constrained correctly. Test the view to confirm it works on multiple simulators.

<details>
  <summary>Image Hint</summary>

  * To load a UIImage you will need to put that image inside of the Assets area in Xcode.
  * PNG files work best for this project
</details>

### Interests Screen

Build another UIViewController. This time, it will contain a StackView of buttons. Make each button's title a interest you have. You should have 5 buttons.

1. Create a new UIViewController inside of Main.storyboard. Don't forget to create a new file/class.
2. Use a StackView and UIButtons to create the view described above.
3. Create a segue from the Main Screen's UIButton to the Interest Screen. Use the "Show" segue.
4. Embed the Main Screen view inside a navigation controller.
5. Create a segue from the Main Screen's UIButton to the Interest Screen. Use the "Show" segue.
6. Make sure everything is constrained correctly. Test the view to confirm it works on multiple simulators.

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
