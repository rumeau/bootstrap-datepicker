bootstrap-datepicker
====================

A datepicker for twitter boostrap, based on http://www.eyecon.ro/bootstrap-datepicker/

Credits to 
==========
http://www.eyecon.ro/


Requirements
============
Jquery 1.8+
Twitter Bootstrap 2.0+


Installation
============
Include the JS and CSS files on your HTML

`<link href="css/datepicker.css" media="screen" rel="stylesheet" type="text/css">`
`<script type="text/javascript" src="js/bootstrap-datepicker.js"></script>`

Usage
=====
Simply call datepicker() on one of your elements

`$('.datepicker-element').datepicker()`

Options
=======
Options may be passed to the component with an object to the constructor

**$('.datepicker-element').datepicker(options)**

|  Name  |  type  |  default  | description  |
| :----: | :----: | :-------: | :----------- |
| format | string | 'mm/dd/yyyy' | the date format, combination of d, dd, m, mm, yy, yyy. |
| weekStart | integer | 0 | day of the week start. 0 for Sunday - 6 for Saturday |
| viewMode | string/integer | 0 = 'days' | set the start view mode. Accepts: 'days', 'months', 'years', 0 for days, 1 for months and 2 for years |
| minViewMode | string/integer | 0 = 'days' | set a limit for view mode. Accepts: 'days', 'months', 'years', 0 for days, 1 for months and 2 for years |
