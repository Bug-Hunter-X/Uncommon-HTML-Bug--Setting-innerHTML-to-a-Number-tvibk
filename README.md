# Uncommon HTML Bug: Setting innerHTML to a Number

This repository demonstrates a subtle bug in HTML where attempting to set the `innerHTML` property of an element to a number (instead of a string) results in unexpected behavior.  The div element will be empty although no error is thrown by the browser.

The bug is present in `bug.html`, and the solution is provided in `bugSolution.html`.