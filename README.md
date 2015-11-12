# TableViewTokenCellTest

NSTableView has issues when using NSTokenFieldCell. This application allows those bugs to be reproduced.

There are two main issues:

* Crash when editing a NSTokenFieldCell more than once.
* Value not propagated via bindings.

These issues are currently being tracked by Apple on their Bug Reported under issue rdar://23497422

For more details, please see the `README.rtfd` document.
