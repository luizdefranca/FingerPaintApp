# Finger Paint App (P*) Assignment

Learning objectives:

Understand custom UIView drawing
Understand how to deal with touch events
Instructions

You'll be implementing a custom view that takes in the user's touches and draws images based on them.

Start simple: choose one colour and one stroke width and implement a view that, when the user is touching with one finger, records the points where the touch moved. Save the lines between those points and then use them to draw lines in the drawRect call of the view.

Draw all of them at first, then refactor your code to use the rect passed to drawRect.

Next, allow the user a way to select different colours. Do you think the interface for that should be inside or outside of the view? How will you save the colours selected?

Stretch Goals

Smoothing

You might notice the drawing lines can be very jerky and have sharp corners. Can you find ways to estimate the path taken by the user’s finger between touches?

Variable Stroke

Change the stroke width to reflect how fast the user is moving their finger: the faster they go, the wider the stroke.

Eraser Mode

Allow the user to switch to the eraser which will allow them to use their finger to erase strokes

Text Support

Allow the user to switch to text mode. Text mode brings up the keyboard for entering text at a location of their choosing

Resources

Creating New Images Using Bitmap Graphics Contexts.
UIResponder Class Reference (in particular the touch-related methods).
Paths (Quartz 2D).
UIBezierPath Object oriented way to do drawing.
