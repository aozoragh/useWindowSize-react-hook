"# useWindowSize-react-hook"
Use the useState() hook to initialize a state variable that will hold the window's dimensions. Initialize with both values set to undefined to avoid mismatch between server and client renders.
Create a function that uses Window.innerWidth and Window.innerHeight to update the state variable.
Use the useEffect() hook to set an appropriate listener for the 'resize' event on mount and clean it up when unmounting.
