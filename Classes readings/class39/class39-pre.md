# Readings: React 2

**Conditional Rendering**:
Conditional rendering in React involves displaying different content or components based on certain conditions.

```jsx
import React from 'react';

function ConditionalRender({ isLoggedIn }) {
  return isLoggedIn ? <p>Welcome, User!</p> : <p>Please log in.</p>;
}

export default ConditionalRender;
```

In this example, the `ConditionalRender` component displays a welcome message if the `isLoggedIn` prop is `true`, and a login prompt otherwise.

**Lists and Keys**:
Rendering lists in React often involves using the `map` function to iterate over an array and create a list of components. Keys are used to help React identify each item uniquely in the list, improving performance and ensuring proper updates.

```jsx
import React from 'react';

function ListExample({ items }) {
  return (
    <ul>
      {items.map((item, index) => (
        <li key={index}>{item}</li>
      ))}
    </ul>
  );
}

export default ListExample;
```

In this example, each item in the `items` array is rendered as an `<li>` element, with a unique `key` assigned to it.

**Forms**:
Handling forms in React involves managing form inputs and their values.

```jsx
import React, { useState } from 'react';

function SimpleForm() {
  const [inputValue, setInputValue] = useState('');

  const handleChange = (event) => {
    setInputValue(event.target.value);
  };

  const handleSubmit = (event) => {
    event.preventDefault();
    console.log('Submitted value:', inputValue);
  };

  return (
    <form onSubmit={handleSubmit}>
      <input
        type="text"
        value={inputValue}
        onChange={handleChange}
        placeholder="Enter something..."
      />
      <button type="submit">Submit</button>
    </form>
  );
}

export default SimpleForm;
```

This example demonstrates a basic form with an input field and a submit button.

**Lifting State**:
Lifting state refers to the practice of managing shared state in a common ancestor component and passing it down to child components as props. This ensures that multiple components can access and modify the same state.

```jsx
import React, { useState } from 'react';

function ParentComponent() {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(count + 1);
  };

  return (
    <div>
      <p>Count: {count}</p>
      <ChildComponent count={count} onIncrement={increment} />
    </div>
  );
}

function ChildComponent({ count, onIncrement }) {
  return (
    <div>
      <p>Child Count: {count}</p>
      <button onClick={onIncrement}>Increment</button>
    </div>
  );
}

export default ParentComponent;
```

In this example, the `ParentComponent` manages the `count` state and passes it as a prop to the `ChildComponent`. When the "Increment" button is clicked in the child component, it calls the `onIncrement` function provided as a prop to update the state in the parent component.

**Composition vs. Inheritance**:
React favors composition over inheritance as a way to build component hierarchies. Instead of inheriting properties or methods from a parent component, you can use composition to include and reuse components within other components. This promotes code reusability and a more flexible component structure.

Here's a simple example of composition in React:

```jsx
import React from 'react';

function Header() {
  return <h1>Header</h1>;
}

function Content() {
  return <p>Content goes here.</p>;
}

function Page() {
  return (
    <div>
      <Header />
      <Content />
    </div>
  );
}

export default Page;
```

In this example, the `Page` component composes the `Header` and `Content` components to create a complete page layout.

## Things I want to know more about

nothing for now.
