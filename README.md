#tsante-scrollarea

##Brief Description
This component has been designed to give a scrollable area with a custom scrollbar. This scrollbar looks like tablet or MAC scrollbars. The scrollbar can also be force to the left or to the right of the area.

##Attributes 
	pos string
		 Set the position of the scrollbar to left or right inside the scrollarea

	vanishing boolean 
		Give the scrollbar the ability to slowly dissipate after a scroll event.

	forced boolean
		Force the displaying of the scrollbar. Useful when using a tablet because the scrollbar will be hidden by default on tablets.



##Method
	scrollTo()
		Allow to scroll to a specific coordinate in the scrollarea


##Browsers compatibility

This component is compatible with the following browsers : 
* Chrome 36+
* Firefox 31+
* Internet Explorer 10+
* Safari 7+

##Exemple

<tsante-scrollarea vanishing="true" forced="false" pos="right"></tsante-scrollarea>
