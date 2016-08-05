
# AnimationSet class

Defines an object for storing and managing CompositionAnimations for an element

## Members

The **AnimationSet** class has this types of members

* [constructors](#constructors)

* [methods](#methods)

* [properties](#properties)

* [events](#events)

### constructors

#### contructor

Initializes a new instance of the [AnimationSet](Microsoft_Toolkit_Uwp_UI_Animations_AnimationSet.md) class.

##### parameters



| name | description | type |
### methods

#### SetDelayForAll(System.Double delayTime)

Ovewrites the delay time on all animations to the specified value

##### parameters



| name | description | type |
#### AddEffectDirectPropertyChange(Windows.UI.Composition.CompositionEffectBrush effectBrush,System.Single value,System.String propertyName)

Adds an effect propety change to be run on StartAsync

##### parameters



| name | description | type |
#### Then()

Wait for existing animations to complete before running any others

##### parameters



| name | description | type |
#### StartAsync()

Starts all animations on the backing Visual.

##### parameters



| name | description | type |
#### Stop()

Stops all animations on the backing Visual.

#### SetDurationForAll(System.Double duration)

Ovewrites the duration on all animations to the specified value

##### parameters



| name | description | type |
#### RemoveDirectPropertyChange(System.String propertyName)

Removes a property change from being run on StartAsync

##### parameters



| name | description | type |
#### AddAnimation(System.String propertyName,Windows.UI.Composition.CompositionAnimation animation)

Adds an animation to be run on StartAsync

##### parameters



| name | description | type |
#### RemoveAnimation(System.String propertyName)

Removes an animation from being run on StartAsync

##### parameters



| name | description | type |
#### AddEffectAnimation(Windows.UI.Composition.CompositionEffectBrush effectBrush,Windows.UI.Composition.CompositionAnimation animation,System.String propertyName)

Adds an effect animation to be run on StartAsync

##### parameters



| name | description | type |
#### AddDirectPropertyChange(System.String propertyName,System.Object value)

Adds a propertyChange to be run on StartAsync

##### parameters



| name | description | type |
### properties

#### Element

Gets the [UIElement](https://msdn.microsoft.com/library/windows/apps/Windows.UI.Xaml.UIElement)

#### Visual

Gets the Visual object that backs the XAML element

### events

#### Completed

Occurs when all animations have completed