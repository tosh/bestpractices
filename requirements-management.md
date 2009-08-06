# motivation

* people forget about bugs and or their current state
* improves documentation and communication

# workflow (spolsky, bugzilla lifecycle)

1. someone identifies a bug and specifies it
  * steps to reproduce
  * what you expected
  * what actually happened instead
2. ticket/issue gets assigned to responsible person
3. person resolves the bug
4. original creator of the issue reviews the bug and
  * may verify that the problem got fixed -> (5.)
  * may reopen it if not satisfied (3.)
5. ticket gets closed 

## todo:

  * include recommendtions on how to write good bug reports
  * add "could not reproduce" or "more input needed" steps to workflow?
  * include bugzilla lifecycle graph?
  * make cross references to feature/issue branching and code review approach using a revision control system
  * mention the importance of ease of use and workflow integration (if people avoid the bug tracking workflow it is useless)
  * broaden the topic to show that features and bugs can be handled similarly -> reqirements management

## side effects:

  * bugs and their state get documented and communicated
  * formal approach that can be combined with scrum and testing
  * bugs actually get fixed because the only person who may close the issue is the one who identified it.

## references

* http://www.joelonsoftware.com/articles/fog0000000029.html (pdf)
* http://www.bugzilla.org/docs/tip/en/html/lifecycle.html (pdf)
