BugFixTableViewController
=========================

This class provides a fix for UITableViewCells flickering and getting stuck as
selected when the swipe-from-left gesture to go back is performed in a certain
manner.

Simply subclass `BugFixTableViewController` instead of
`UITableViewController` and you'll be good to go! If you override any
of these four methods, just **remember to call super** on them.

Before
------
![Before](https://raw.githubusercontent.com/aclissold/BugFixTableViewController/master/Before.gif)

After
-----
![After](https://raw.githubusercontent.com/aclissold/BugFixTableViewController/master/After.gif)
