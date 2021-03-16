# State and LifeCycle

## How to create a clock component

## As a function:

`function Clock(props) {`

    `return (`

    `<div>`

     `<h1>Hello, world!</h1>`

      `<h2>It is {props.date.toLocaleTimeString()}.</h2>`

    `</div>`

  `);`

`}`

## As a class

`class Clock extends React.Component {`

 ` render() {`

    `return (`

      `<div>`

        `<h1>Hello, world!</h1>`

        `<h2>It is {this.props.date.toLocaleTimeString()}.</h2>`

      `</div>` 
      `);}}`

## Adding local state to a class

change the `<h2>` to:

`<h2>It is {this.state.date.toLocaleTimeString()}.</h2>`
<br>
<br>

then add a class constructor that assigns the initial `this.state:`

`class Clock extends React.Component {`

`constructor(props) {`

`super(props);`

`this.state = {date: new Date()};`
  `}`

State is data in your application

Whats your name?

How many videos you have?

number of tweets.

once that data changes your ui updates

it only updates that specific part making it update really fast.

State just like props can only be passed down to children

## Events

Events are like events on the dom with different syntax

you cannot use false. instead use `preventDefault`

