------------------
Global Folder:
------------------

The global folder holds no design or css itself, it only holds pieces
of design that can be utilized throughout the whole css structure. 

------------------
_base.scss:
------------------
This file is used as an import file. No variables, functions, mixins, 
or extendables are to be placed here. This file is imported into style.scss. 

------------------
_extendables.scss
------------------
This file is to be used for large sentions of generic css that can be 
reused by other selectors. Call an extenable using @extend selector. Where
selector is the proper selector as found in the css, #selector or .selector 

------------------
_mixins.scss
------------------

Mixins are used to hold reusable css that can contain variables. 
Call a mixin using @include "name_of_mixin". 

------------------
_variables.scss
------------------

Used for common variables that are used throughout the site. 
Name a variable as 

$variable_name: variable; 

Call the variable using $variable_name. 

Example: 
	$times: 'Times New Roman', times, serif;

	font-family:$times;

------------------
FYI
------------------
 After the initial set up there should be very little need to touch this file. 