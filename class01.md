# Introduction to React and Components
## What is a component?
### The site is divided using the component into separate interfaces, to analyze the design into small particles, each with different properties, and the component is a replaceable and reusable software object.
## What are the charactistics of a component?
- replaceable.
- reuse.
- The ability to use it in different locations.
- independent. 

## What are the advantages of using component based architecture?
1. Ease of development.
2. Low cost and easy to deploy.
3. Independent and easy to modify.

## What is props short for?
### It is a component-based library that breaks down the user interface into reusable parts.


## How are props used in React?
- Firstly, define an attribute and its value(data)
- Then pass it to child component(s) by using Props
- Finally, render the Props Data

``````````
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
      </h1>
    );
  }
}
``````````

## What is the flow of props?
It is one of the characteristics of React as the data flows in only one-way.

