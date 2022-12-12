---
title: Live Coding Example Page
description: How to implement live coding in Docusaurus
---

## Live Coding with React in Docusaurus

```jsx live
function Examplelive(props) {
  const [count, setCount] = useState(0);

  return (
    <div>
      <h1>{count}</h1>
      <button onClick={() => setCount((p) => p + 1)}>Add</button>
      <button onClick={() => setCount((p) => p - 1)}>Subtract</button>
    </div>
  );
}
```
