# React useEffect Missing Dependency Bug
This repository demonstrates a common bug in React's `useEffect` hook where a missing dependency leads to unexpected behavior.  The `count` state variable is not included in the dependency array, causing the `setInterval` to persist even after the component is unmounted, resulting in a memory leak and potentially unexpected behavior. The solution demonstrates proper dependency array management to resolve this issue.