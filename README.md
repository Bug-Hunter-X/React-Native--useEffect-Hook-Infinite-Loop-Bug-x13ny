# React Native: useEffect Hook Infinite Loop Bug

This repository demonstrates a common error in React Native applications involving the `useEffect` hook.  The provided code exhibits an infinite loop because the effect's dependencies are not explicitly listed in the dependency array. 

The `bug.js` file contains the erroneous code, highlighting the problem.  The `bugSolution.js` file presents the corrected code with the proper dependency array implemented.  This highlights the importance of properly managing dependencies within `useEffect` for performance and stability.