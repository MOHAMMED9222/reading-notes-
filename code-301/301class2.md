*Reading Notes*

## REACT

**Static getDerivedStateFromProps()** The static getDerivedStateFromProps is the first React lifecycle method to be invoked during the updating phase.

**Mounting**
When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

**Updating**
Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

-static getDerivedStateFromProps 

-shouldComponentUpdate 

-render

-getSnapshotBeforeUpdate 

-componentDidUpdate

-UNSAFE_componentWillUpdate

-UNSAFE_componentWillReceiveProps

**Unmounting**
The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

**constructor()**
The constructor for a React component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance. 

**componentDidMount()**
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

**setState()** can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.

**shouldComponentUpdate()**
The default behavior in react is to rerender after every state change. Setting shouldComponentUpdate() to false allows you to prevent this from happening. This is in order to optimize performance. If you want to use this method, it may be better to use PureComponent instead, which performs a shallow comparison of props and state. If you do decide to use this method, be sure to check the previous props and state with the current props and state. If shouldComponentUpdate() returns false, then UNSAFE_componentWillUpdate(), render(), and componentDidUpdate() will not be invoked.

**getSnapshotBeforeUpdate()**
This is another rarely used method that allows you to capture a picture of the DOM to check it before actually changing anything on the DOM.

**componentDidUpdate()**
This method is useful for performing network requests after a change has occurred.

**componentWillUnmount()**
This method allows you to clean up the DOM and netwrok requests/ subscriptions.

