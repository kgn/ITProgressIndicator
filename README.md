ITProgressIndicator
===================

A replacement class for `NSProgressIndicator` driven by Core Animation.
It's highly customisable and much more efficient than `NSProgressIndicator`.

`ITProgressInidicator` was created for <a href="http://playbyplayapp.com">Play by Play</a>, funded by <a href="http://davidkeegan.com">David Keegan</a>.

<img src="./Demo.gif" alt="" />


Usage
-----

### Copy files

Copy the following files:

* `ITProgressIndicator.h`
* `ITProgressIndicator.m`
* `NSBezierPath+Geometry.h`
* `NSBezierPath+Geometry.m`

Make sure to copy them to the project, and to add them to the target.


### Use in a project

Make sure to check out the sample project.
Simply drag a custom view onto your window and set it's custom class to `ITProgressIndicator`.

To customise your progress indicator, use the following properties:

<<<<<<< HEAD
/// @property isIndeterminate - Indicates if the view will show the progress, or just spin
@property (nonatomic, setter = setIndeterminate:) BOOL isIndeterminate;


/// @property progress - The amount that should be shown when `isIndeterminate` is set to `YES`
@property (nonatomic) CGFloat progress;


/// @property animates - Indicates if the view is animating
@property (nonatomic) BOOL animates;


/// @property hideWhenStopped - Indicates if the view will be hidden if it's stopped
@property (nonatomic) BOOL hideWhenStopped;


/// @property lengthOfLine - The length of a single line
@property (nonatomic) CGFloat lengthOfLine;


/// @property widthOfLine - The width of a single line
@property (nonatomic) CGFloat widthOfLine;


/// @property numberOfLines - The number of lines of the indicator
@property (nonatomic) NSUInteger numberOfLines;


/// @property innerMargin - The distance of the lines from the middle
@property (nonatomic) CGFloat innerMargin;


/// @property animationDuration - Duration of a single rotation
@property (nonatomic) CGFloat animationDuration;


/// @property gradualAnimation - Defines if the animation is smooth or gradual
@property (nonatomic) BOOL steppedAnimation;

/// @property color - The color of the progress indicator
@property (nonatomic, strong) NSColor *color;


You can also override the following method to achieve your own custom animation:

/**
 *  Override this method to achieve a custom animation
 *
 *  @return CAKeyframeAnimation - animation which will be put on the progress indicator layer
 */
- (CAKeyframeAnimation *)keyFrameAnimationForCurrentPreferences;


    
### License

    DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
    Version 2, December 2004 
    
    Copyright (C) 2013 Ilija Tovilo <support@ilijatovilo.ch> 
    
    Everyone is permitted to copy and distribute verbatim or modified 
    copies of this license document, and changing it is allowed as long 
    as the name is changed. 
    
    DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
    TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

    0. You just DO WHAT THE FUCK YOU WANT TO.

### Help

If you have any questions, feel free to let me know at support@ilijatovilo.ch
=======
    /// @property isIndeterminate - Indicates if the view will show the progress, or just spin
    @property (nonatomic, setter = setIndeterminate:) BOOL isIndeterminate;
    
    /// @property progress - The amount that should be shown when `isIndeterminate` is set to `YES`
    @property (nonatomic) CGFloat progress;
    
    /// @property animates - Indicates if the view is animating
    @property (nonatomic) BOOL animates;
    
    /// @property hideWhenStopped - Indicates if the view will be hidden if it's stopped
    @property (nonatomic) BOOL hideWhenStopped;
    
    /// @property lengthOfLine - The length of a single line
    @property (nonatomic) CGFloat lengthOfLine;
    
    /// @property widthOfLine - The width of a single line
    @property (nonatomic) CGFloat widthOfLine;
    
    /// @property numberOfLines - The number of lines of the indicator
    @property (nonatomic) NSUInteger numberOfLines;
    
    /// @property innerMargin - The distance of the lines from the middle
    @property (nonatomic) CGFloat innerMargin;
    
    /// @property animationDuration - Duration of a single rotation
    @property (nonatomic) CGFloat animationDuration;
    
    /// @property gradualAnimation - Defines if the animation is smooth or gradual
    @property (nonatomic) BOOL steppedAnimation;
    
    /// @property color - The color of the progress indicator
    @property (nonatomic, strong) NSColor *color;


You can also override the following method to achieve your own custom animation:

    /**
     *  Override this method to achieve a custom animation
     *
     *  @return CAKeyframeAnimation - animation which will be put on the progress indicator layer
     */
    - (CAKeyframeAnimation *)keyFrameAnimationForCurrentPreferences;
>>>>>>> be4700ae28415131431ba0bbe9def4c515645ca6
