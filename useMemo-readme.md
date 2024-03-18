
# useMemo

### Explanation

- useMemo is a hook used to memoize values
- useMemo contains two params, one is callback to perform activities and another one is dependencies arrays where the callback will be executed when changes detected on dependencies
- useMemo returns a value based on the calculations performed
- useMemo prevents unnecessary re-computation of expensive values when there is no change on dependencies

### Usage

- Perfoming calculations
- Perfoming filter operations

#### Example 1

- Perfoming calculations and memoizing values

![decode-example-image](https://i.ibb.co/PCgX9yS/Screenshot-from-2024-03-18-14-58-50.png)

#### Example 2

- Filtering data based on search value 

![decode-example-image](https://i.ibb.co/cDt2Pqj/Screenshot-from-2024-03-18-15-08-22.png)
