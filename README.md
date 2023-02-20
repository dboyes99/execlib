# execlib
Tools to manage libraries of REXX code snippets to perform common tasks and include the snippets programatically.

This package includes tools to create a common library of REXX routines to perform common tasks when developing CMS EXECs. The needed routines are specified using inline comments of the form: 

/* $$INCLUDE <membername> -- comment           */

Routines are inserted immediately following the comment line in the original file by typing INLINE at the XEDIT command line. 

The BLDMAC command builds a CMS MACLIB (default EXECLIB MACLIB) from a series of <membername> COPY files. The first line of each COPY file must be COPY <membername> or MACRO <membername>, See the description of the CMS MACLIB command for more information on the difference between COPY and MACRO.


