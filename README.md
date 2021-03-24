# command-line-params
A Racket macro to automate command line parameter definitions

### How to use?
<pre>
(define-command-line-params my-path my-second-parameter)
</pre>
Defines two variables (my-path and my-second-parameter) which contain the two first command line parameters. An error message with the missing parameter name is automatically generated and displayed if a parameter is missing on the command line.
