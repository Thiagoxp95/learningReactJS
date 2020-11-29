# **useState, useEffect Hooks** 

```js
export default function App() {
    const [currentState, setNewCurrentState] = useState('initialState')
    //inside useState, the element is called or invoked on every render if used 
    // like this.
}

function functionToBeCalledOnJSX(){
    setNewCurrentState = (something => something + 1 )
    // it already knows that something is the current state registered before.
    // can not use the literal variable i.e. currentState

}