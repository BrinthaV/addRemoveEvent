JavaScript eventListener  Method

The EventTarget interface provides multiple methods for handling the events in javascript on DOM objects.

addEventListener() :
It is very easy to add an event to any object in javascript using addEventListener(). We can even add multiple event listeners to a single object of the same type. These events will not override each other and will execute properly as expected without affecting each other’s working.
Events Added In the Code for addEventListener():
click : Button color changed to LightBlue and the message displayed as “Button was clicked!”
Mouseover: Button color changed to Green and the message displayed as “Mouse over button Action!"
mouseenter: Button color changed to Green and the message displayed as “Mouse Enter Event on the button!"
mouseleave: Button color changed to Green and the message displayed as “Mouse left from the button!"
keydown(Enter): Button color changed to Red and the message displayed as “Enter key pressed!”.

----------------------------------------------------------------------------------------------------------------------------------

removeEventListener() :
The removeEventListener() method removes event handlers that have been attached with the addEventListener() method:

Events Added In the Code for removeEventListener():

Click: Onclick of the button, increase the click count and display the message with click count. Once it reaches 3, the click event removed and display the message as “You clicked the button 3 times. Event listener removed! Double Click to Enable the Button”
dbclick: once doubleClick the button, the button color changed to Green and the message displayed as “Button Enabled. Presse Enter key to start again”
keydown: (Enter): Button color changed to lightcoral and the message displayed as “Enter key pressed! Refresh Page to Start Again”.
    

