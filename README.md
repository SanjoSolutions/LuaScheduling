# Scheduling

A library for scheduling. This library can save add-on developers some work.

**Functions included:**

* **Scheduling.doEachFrame**: a function for registering a function that is run each frame (via "OnUpdate"). The function also returns a table with the method "Cancel", that can be called to cancel the running of the previously registered function.
