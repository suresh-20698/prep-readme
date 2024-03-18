
# useEffect

### Explanation

- useEffect is a hook used to enables functional components to perform side effects
- useEffect accepts two params, one is a callback function to be executed and dependency array where the callback will be executed when there is a data change in provided dependencies
- useEffect will get called once after the component is mounted if the dependency array is provided empty

### Usage

- Data fetching
- Side effects based on dependencies
- Subscription and cleanup activities

#### Example 1

- Fetching data using useEffect

![decode-example-image](https://i.ibb.co/9Hmk6LX/Screenshot-from-2024-03-18-14-19-07.png)

#### Example 2

- Using dependencies to change title based on click count

![decode-example-image](https://i.ibb.co/p0GvF2p/Screenshot-from-2024-03-18-14-22-14.png)

#### Example 3

- Using useEffect to capture mouse positons by adding `addEventListener` as subscription and removing `removeEventListener` as clean up (while unmounting)

![decode-example-image](https://i.ibb.co/N3CZsYQ/Screenshot-from-2024-03-18-14-26-45.png)
