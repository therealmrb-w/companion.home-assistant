---
title: "Android Widgets"
id: 'android-widgets'
---

The ![Android](/assets/android.svg) Android app allows the user to create widgets on the home screen so the user can perform a variety of actions like execute a service call, display the state of an entity or even render a template. You can add the widget like you normally would for any app depending on your devices launcher. The widget will not work when Data Saver is enabled, you will also need to ensure that background data for the app is enabled. If you notice that a widget is no longer working try to recreate it. Widgets can also be edited by navigating to Companion App > Manage Widgets, if you are on Android 12 you can also edit the widget by long pressing it and clicking on the edit icon.

Widgets can also be added from the Manage Widgets settings page, as long as the device supports it.

## Camera

This widget will update every hour or when it is tapped. The widget will just contain the latest snapshot from the selected camera.

1.  Long press on any open space in the home screen
2.  Scroll down to Home Assistant in the widget list
3.  Drag the Camera Widget to an open space on the home screen
4.  Enter the Entity ID of the camera you wish to use
5.  Save the widget

## Entity State

This widget will update every 30 minutes or when it is tapped. This widget will allow the user to select any entity they wish to get the state and an attribute from as well as setting the text size and adding a custom separator between the state and attributes.

1.  Long press on any open space in the home screen
2.  Scroll down to Home Assistant in the widget list
3.  Drag the Entity State widget to an open space on the home screen
4.  Enter the Entity ID you wish to view the state of
5.  If needed select the attribute checkbox and select the attribute you wish to add to the state
6.  If needed adjust the widget text size
7.  If needed add a custom separator to sit between the state and attribute
8.  Supply a name for the widget
9.  Save the widget


## Media Player

This widget will let the user control any media player on their home screen. There are a couple of options available to hide or show the seek and skip buttons.

1.  Long press on any open space in the home screen
2.  Scroll down to Home Assistant in the widget list
3.  Drag the Media Player widget to an open space on the home screen
4.  Enter the Entity ID you wish to control
5.  If needed hide the Seek/Skip buttons, or show the Volume buttons
6.  Supply a label for the widget
7.  Save the widget

## Service Call

This widget will make the service call when it is tapped. The user will see a green check mark if the call was successful and red if not. Red would indicate either the widget was not setup properly, the Home Assistant server is unavailable or some other error that would be indicated in the Home Assistant log.

1.  Long press on any open space in the home screen
2.  Scroll down to Home Assistant in the widget list
3.  Drag the Service Call widget to an open space on the home screen
4.  Select the service call you wish to perform
5.  Fill in the required service data for the selected service call
6.  Supply a name and icon for the widget
7.  Save the widget


## Template

This widget will display any text that you wish to show in a widget using [Home Assistants templating feature](https://www.home-assistant.io/docs/configuration/templating/). This is an advanced feature but allows the user to display a wide variety of data. The widget will render the templates live below the text field so you can preview what it would look like. 

You may also use HTML to format the text displayed such as adding a new line, making something bold or changing the color. <br /><br />

1.  Long press on any open space in the home screen
2.  Scroll down to Home Assistant in the widget list
3.  Drag the Template widget to an open space on the home screen
4.  Fill in the template data and observe the rendering below
5.  Save the widget
