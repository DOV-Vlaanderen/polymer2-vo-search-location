## Copy of vaadin-combo-box component

We were forced to copy vaadin-combo-box commponent: bug internal browser in iOS (The list of suggestions was always behind the keyboard). 
There was no way to override the property 'alignedAbove' in the dropdown component because of a smart 
function (_shouldAlignAbove()) that set the property back to false event if it should be true.

