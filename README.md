Slider in native js.

A classic slider that places images on the background of blocks assembled horizontally.

The settings object received in the parameters must have properties:

sliderStringSelector - a selector for the block containing slides.

sliderButtonLeftSelector - the selector of the button that calls the swipe left function.

sliderButtonRightSelector - the selector of the button that calls the swipe right function.

imageDivClassName - the name of the image blocks class.
timeout is an integer indicating at what interval in milliseconds the auto scroll function will be called. (If the auto scroll function is not needed, this property should be skipped)

buttonAnimation - a boolean value indicating whether to call the animation of the buttons when pressed (animation so far only works by resizing the button's background image from width: 100% to width: 90% and back).

fullHeightSize is a boolean value. If this property is set to true, then the image will be wrapped in one more wrapper and will be fully displayed vertically.

ImageWrapperClassName - the name of the wrapper class, must be specified when fullHeightSize: true.

widthOfImgWrapper (temporarily) - the width of the block with the image in integer format.

insertText - boolean, if true, text will be added to slides (see next points).

text - an array containing lines with text (the line index in the array corresponds to the ordinal number of the slide).

textClassName - an array of class names for text (the index of the class name in the array corresponds to the index of the line in the array and the ordinal number of the slide).
