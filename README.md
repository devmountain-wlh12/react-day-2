This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# React Day 2

## The Props Pattern:

1. Sending a prop from parent to child, in the parent component:
```javascript
render() {
  return (
    <div>
      <ChildComponent prop=val name='Jonathan' .../>
    </div>
  )
}
```

2. Receiving a prop from the parent, in the child component:
```javascript
constructor(props) {
  super(props)
  ...
}
...
render() {
  <div>
    Name: {this.props.name}
  </div>
}
```