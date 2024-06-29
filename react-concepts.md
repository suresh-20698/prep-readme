
# React Concepts

## How React works

- ### JSX (JavaScript XML)
    React Application allows to use HTML code inside a Javascript file, the concept is known as Javascript XML (JSX), How deos React handle this approach by using the help of Babel to convert them.

- ### Component Based
    React Application is fully consists of smaller components which acts like a building blocks  to construct an React application, React Components are can be built using Class Components or Functional Components where both can be used for things such as conditional rendering, implementing logics, resuable writtern code for multiple use cases. 

- ### State and Props
    State and Props are special variables provided by React for handling data management within the React Application and also React re-renders components based on the mutation happens to state or props.

    State can be used to manage within a component.

    Props can be used as read-only attribute which can be sent from parent to child component.

- ### Lifecycle Methods and Side Effects
    Lifecycle Methods and Side Effects are useful which makes React Components more interactive, It allows to do specific operation based on the Component runs such as methods like componentDidMount, componentDidUpdate, componentWillUnmount and useEffect respectively.

- ### Virtual DOM and Reconciliation
    React doesn't update the DOM directly instead it has few mirror copies of DOM which known as Virtual DOM, React uses an algorithm to compare the Real and Virtual DOM, the process of comparing is known as Reconciliation.

- ### DOM and Event Handling
    React allows to interact with the DOM and Events provided by the Javascript, which helps in performing operation based on condition or demand, example: changing Page title when route changes.

## React Reconciliation

- ### Virtual DOM
    Instead of updating the changes detected to Real DOM, React makes a mirror of copies of DOMs known as Virtual DOM, They are mainly used for comparison purpose to find the difference in Elements and Contents modified, This increases the performance of the application my making bulk updates at once. 

- ### Diff Algorithm
    For comparing the copies of Virtual DOM and Real DOM, React uses Diff algorithm which mainly uses TREE LIKE STRUCTURE.

    - #### Comparing Element Types
        If the element type changes React will destroy the old tree and build a new tree.

    - #### Updating Props and Attributes
         If only the props have changed, React will update the attributes of the existing DOM element.

    - #### Recursively Comparing Children
        React then recursively compares the children of the elements.

    - #### Handling Lists with Keys
        When comparing lists, React uses the key props to identify and match elements between the old and new lists using HASH.

- ### Reconciliation
    The process of Comparing, Updating and triggering lifecycle methods and side effects are collectively called Reconciliation.

## Caching Techniques in React

- ### Memoization
    Using Hooks like useMemo, useCallback and React Memo for minimalizing renderers.

- ### Code splitting and Lazy loading
    Above techniques will provides improvement in performance by loading components based on demand.

- ### Optimizing Network Requests with Caching
    Using popular libraries like axiox or React query which provides elements to handle caching for Network calls to server.

- ### Browser storage
    Using browser storage to store limited data, since data will be preserved between renders.

## How to make React Application work faster

- #### Lazy loading

- #### Code splitting

- #### Memoization

- #### Profiling and Optimizing

- #### React Windowing

- #### Micro frontends

- #### Tree Shaking
