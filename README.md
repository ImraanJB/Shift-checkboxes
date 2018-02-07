# Shift-checkboxes
When a user clicks a checkbox, holds Shift, and then clicks another checkbox a few rows down, all the checkboxes inbetween those two checkboxes should be checked.
Created with the help of Wes bos.


What I learned on this mini-project.

let
Using let for variable assignments is useful when you expect the the variable to change.

let lastChecked;
This is different to const which is for variables you wish to remain constant throughout the script.

shiftKey
You can use the shiftKey property of an event to check if its active

event.shiftKey;
In this case, this is used for a click event

checked
To check whether a checkbox has been checked or not, you can assess its checked property (I heard it too...)

checkbox.checked;
