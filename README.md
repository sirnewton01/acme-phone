# acme-phone

This is a design for a simple Plan 9 acme inspired "smart" phone. The default mode of
the phone is to present and manipulate text content using touch screen gestures. The text
forms much of the basic interface. The jumping off point is the home file, which is just a
simple text file where you can write notes or commands to launch other programs. Each file
and running program instance has its own window that can be flipped through using the two
buttons on the side of the phone. Commands can take full control over the window to create
any graphical interface that they want.

Once your home file is set up to suit your needs the UI is designed to make it easy to
read text that is there using single finger drag to scroll and the left/right buttons to
switch contexts. The next easiest task is to be able to execute commands and navigate
using the content you have prepared. Finally, manipulating text is possible to facilitate
customization of the device and content creation is quite doable but necessarily requires
more attention and therefore has a more involved workflow.

Since the conventions borrow much from Plan 9 it should be possible to use it to power the
phone.

## UI Mockup

You can look at the [mockup image](acme-phone-ui-mockups.png) to get a general sense of how the phone operates.

## TODO

* Develop a gesture to "Del" a window
* Demonstrate lock screen and its sandbox
* Show cell phone signal strength
* Keyboard customization using /dev/kbd file
* Show how to input Unicode characters without the native keyboard for them
* Begin designing the overview of how the back-end works
  * Plan 9 system, sandbox for the lock screen, how OS boot works (network or local), authentication
