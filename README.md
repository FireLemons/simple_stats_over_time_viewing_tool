### Installation
`npm i`

### Run locally
`npm run start`

### Data Format  
The data points must be in an array. Each point represented by an object with numerical values or a tuple where the first element is a string that will label the point and the second element is again an object with numerical values. json5 syntax is supported.  

#### Example  
```json5
[
  {
    a: 0,
    b: 0,
    c: 1
  },
  ['label',{
    a: 1,
    b: 4,
    c: 3
  }],
  {
    a: 2,
    b: 2
  }
]
```
