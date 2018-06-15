# js-eval

A simple command line interface to the browser's js interpreter.  This works similarly to the web console in Firefox, with some additional accessibility tweaks.

- type a command and a result appears below in the output pane
- Each result is in a container marked up as a live region, so is announced as it is produced.
- each result is separated by a heading wrapping the text of the command that produced that result. This makes it easy to scan through the results via screen reader.
- Move through input history with up/down arrows when focused in the input box.
	+ When a history command is placed in the input box, pressing tab takes you immediately to the result it produced in the output pane.
