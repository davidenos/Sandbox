#A few notes on this sample:

1. Use ocp-iframe.html to view the mockup within an iframe
2. Currently the message is editable, but I assume if this were a petition rather than a constituent email that the group would not want it to be so, in which case I would add readonly="readonly" to the text area tag. (seems like a redundant way to go about it since you can use just readonly , but this way ensures XHTML compatibility)
3. I created a modal window for the Facebook sign in when the button is clicked, but did not yet include the function to fill in the data pulled from Facebook since it would require an organizational ID to validate.