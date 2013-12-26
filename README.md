myselect - custom html `<select>` widget.
=========================================

This widget replaces the browser's native `<select>` tag widget.

How it works:
-------------

It hides all the `<select>` tags on the page, replacing them by itself.

Live demo:
----------

<iframe src="http://szyryanov.github.io/Portfolio/HtmlSelect/live-demo.html" width="150" height="100" align="left">
    Your browser does not supports frames.
</iframe>

[Click here](http://szyryanov.github.io/Portfolio/HtmlSelect/live-demo.html "widget live demo page")

Features:
---------

* amusing appearance
* similar appearance for all major browsers
* mouse interaction
* keyboard interaction
* unobtrustive
* graceful degradation
* the selected valie is two-binded to the original `<select>` tag
* customizable widget structure (you can edit the myselect.html file)
* customizable widget appearance (you can edit the myselect.css file)

How to use:
-----------

1. Download the [widget package][distro]
2. Extract into an appropriate subdirectory on your site, e.g. "/widgets/myselect"
3. Add the jQuery library reference on your page, if not added yet
4. Add the widget script reference on your page

[distro]: http://szyryanov.github.io/Portfolio/HtmlSelect/files/myselect.zip "widget package"

For example:

        ... your page content ...
        <script src="js/jquery.js"></script>
        <script src="widgets/myselect/myselect.js"></script>
    </body>
    </html>

If you want to keep some `<select>` tag "as is", then add "myselect-skip" class to the tag (e.g. `<select class="myselect-skip">`).

If you want to see both the native widget and the customized one for some `<select>` tag, then add
"myselect-debug" class to the tag (e.g. `<select class="myselect-debug">`).

Limitations:
------------

The widget was not intended for real use but for education/training purpose. It replaces the `<select>` tag only. Any serious usage requires to customize other widgets too in order to make a consistent look (e.g. textbox, checkbox, radiobutton etc.).

So, the widget is ready to use, but with the following limitations:

* "multiple" (listbox-like) mode is not supported;
* `<optgroup>` feature is not supported;
* The original `<select>` tag positioning is not applied to the widget. You can wrap the `<select>` into `<span>` and apply the positioning to the `<span>` tag. 

How it looks in major browsers:
-------------------------------

coming soon

Graceful degradation:
---------------------

coming soon

License:
--------

This projected is licensed under the terms of the MIT license.

