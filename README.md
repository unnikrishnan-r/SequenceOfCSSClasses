# SequenceOfCSSClasses

I am trying to test the sequence in which CSS classes are applied, when an element has multiple classes (and competing) defined.

eg: 
I have a Green Button (class green-button) and a Blue Button (blue-button)
I then set up a 3rd button with  "green-button blue-button"

If the CSS has green-button first:
      The 3rd button will take blue-button's property

If the CSS has blue-button first:
      The 3rd button will take green-button's property


Basically the sequence in which classes are specified in html has no relevance. The position of the class in CSS is the key factor.

References:
https://stackoverflow.com/questions/1321692/how-to-specify-the-order-of-css-classes
https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Cascade_and_inheritance

Video of Test Results:
https://drive.google.com/file/d/1hTayK7dSjVBJPas8Ubm9z5Houy9DibEJ/view

      