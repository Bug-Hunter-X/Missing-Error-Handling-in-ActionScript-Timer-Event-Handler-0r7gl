This example demonstrates a common error in ActionScript:  missing error handling in an event handler. Specifically, a TimerEvent handler is shown without any error handling.  If an exception is thrown inside the timer's event handler, the application might crash.  The solution demonstrates how to add a try-catch block to handle potential errors gracefully.