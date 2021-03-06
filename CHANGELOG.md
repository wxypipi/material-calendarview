Change Log
==========

Version 0.5.0 *(2015-06-17)*
----------------------------

* Change: There are several factory methods on `CalendarDay` which should be used in place of the now deprecated constructors
* Bugfix: You can now clear the selected date. Either by passing null or calling `clearSelection()`
* New: You can now supply a custom `DayFormatter` to format day labels.

Version 0.4.0 *(2015-05-18)*
----------------------------

* Change: Revamp DayViewDecorators to be more efficent. See README for differences.

Version 0.3.2 *(2015-05-03)*
----------------------------

 * New: Added ability to change the first day of the month
 * New: Added month change listener

Version 0.3.1 *(2015-04-23)*
----------------------------

 * New: Added DayViewDecorator and DayViewFacade to allow for day decorating

Version 0.3.0 *(2015-04-15)*
----------------------------

 * Change: Namespaced library resources. Everything is now prefixed with `mcv_`
 * New: Widget resizing is now possible by setting the tileSize
     * Change: XML layouts are no longer used
     * Change: Default tile size is now an integer resource

Version 0.2.5 *(2015-03-11)*
----------------------------

 * New: Customize labels for weekdays and months

Version 0.2.4 *(2015-03-06)*
----------------------------

 * Bugfix: Full fix issue that was supposed to be fixed in 0.2.2
 * Bugfix: Text didn't center on RTL apps, default the text alignment to center

Version 0.2.2 *(2015-02-26)*
----------------------------

 * Bugfix: Using `Date` for setting anything in the library wasn't getting set correctly
 * New: Added `Date` variants for min and max setters


Version 0.2.1
-------------

 * Start of ChangeLog
