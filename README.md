# jquery.removeevent

Fast "remove" event for elements in jQuery

Add `<script type="text/javascript" src="jquery.removeevent-min.js"></script>` to your code, and now every element removed via jQuery's `remove`, `empty` etc. will receive a "remove" event.

* This uses the snippet that jQuery UI uses - while detecting first if jQuery UI is present - and abort if it is.
* Supports amd/commonjs etc.
