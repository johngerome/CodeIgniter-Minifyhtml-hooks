CodeIgniter-Minifyhtml-hooks
============================

A CodeIgniter Hooks that will Minify the HTML, Reducing network latency, enhancing compression, and faster browser loading and execution.

Installation
-----------------

Copy `/application/config/hooks.php` and 
`/application/hooks/Minifyhtml.php` 
into your `application` folder Project

Modify your `/application/config/config.php` into this:
```php
	-/*
	|--------------------------------------------------------------------------
	| Enable/Disable System Hooks
	|--------------------------------------------------------------------------
	|
	| If you would like to use the 'hooks' feature you must enable it by
	| setting this variable to TRUE (boolean).  See the user guide for details.
	|
	*/
	$config['enable_hooks'] = TRUE;
```

and your Done!

------------------------------------------------------
Everytime you call `$this->load->view('view/view_file');`, 
output function in Minifyhtml Class will be used.

Change Log
==========
**2nd January 2017**
Added an ability to skip **style** and **script tags**

