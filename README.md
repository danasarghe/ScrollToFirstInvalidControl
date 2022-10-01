# ScrollToFirstInvalidControl
Imagine that the very first control is invalid and a user clicks the submit button. Since, the element is off-screen,
she/he cannot figure out immediately what went wrong, because an error message is rendered just below the control element.
The solution to the problem was to scroll a document, once an invalid form has been submitted,
so that the first invalid control appeared at the top of the viewport 
