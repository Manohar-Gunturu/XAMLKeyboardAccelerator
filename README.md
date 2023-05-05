# XAMLKeyboardAccelerator
Sample app to show the KeyboardAccelerator bug for dynamic overflow CommandBar.

Open the app, maximize the app window until you see delete button and the press delete key in the keyboard.

<img width="689" alt="image" src="https://user-images.githubusercontent.com/6416138/236568184-284fe7cd-0624-407d-a11e-741a888c24c5.png">

you will see the delete pressed event.

Resize down the window until delete button goes into overflow menu. And then presse the delete key in the keyboard, event doesn't fire.

<img width="467" alt="image" src="https://user-images.githubusercontent.com/6416138/236568633-99b2377a-17b4-4055-8d22-37c98c38dae0.png">



