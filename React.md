#What is useState() in React?
The useState() is a built-in React Hook that allows you for having state variables in functional components.
It should be used when the DOM has something that is dynamically manipulating/controlling.

In the below-given example code, 
The useState(0) will return a tuple where the count is the first parameter that represents the counter’s current state and the second parameter setCounter method will allow us to update the state of the counter.

...
const [count, setCounter] = useState(0);
const [otherStuffs, setOtherStuffs] = useState(...);
...
const setCount = () => {
   setCounter(count + 1);
   setOtherStuffs(...);
   ...
};
We can make use of setCounter() method for updating the state of count anywhere. In this example, we are using setCounter() 
inside the setCount function where various other things can also be done. The idea with the usage of hooks is that we will 
be able to keep our code more functional and avoid class-based components if they are not required.


#Give me two most significant drawbacks of React
Integrating React with the MVC framework like Rails requires complex configuration.
React require the users to have knowledge about the integration of user interface into MVC framework.
