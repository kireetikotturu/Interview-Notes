# REACT INTERVIEW PREPARATION QUESTIONS — MERN STACK

---

# REACT (CONCEPTUAL + TECHNICAL)

1. What is React **
2. What is single page application (SPA) **
3. What are components in React and how are they useful ***
4. What is JSX and why is it used in React ***
5. What are props and state (difference between them) ***
6. What is the difference between class components and functional components ***
7. What are React Hooks ***
8. Explain useState, useEffect, useLayoutEffect, useMemo, useCallback, useRef ***
9. What are custom hooks and when to use them ***
10. Explain React.memo and how it helps in optimization ***
11. Explain Context API and how to integrate it ***
12. What is prop drilling and how to avoid it ***
13. When and how to use lazy loading ***
14. What is Virtual DOM ***
15. What is reconciliation in React (how React updates DOM) ***
16. How to route between pages in React **
17. What are error boundaries in React ***
18. What are controlled and uncontrolled components ***
19. What are keys in lists and why are they important ***
20. What is React Fragment and why is it used **
21. What are higher-order components (HOCs) **
22. What are lifecycle methods (mount/update/unmount) in class components **
23. What is Redux and Redux Toolkit? How do you create a store? ***
24. How to structure a React application folder **
25. How will you handle authentication in frontend and where to store the token ***
26. What are interceptors in Axios ***
27. How to handle state in large applications (Context, Redux, Zustand, MobX, Jotai) ***
28. How to debug a React application ***
29. Is React a framework? **
30. How to handle large number of records in a table (virtualization) ***
31. What is React Portal and when to use it **
32. Difference between useEffect and useLayoutEffect ***
33. What is useReducer and when to use it **
34. What is React.StrictMode and why is it used **
35. What are synthetic events in React **
36. What is code splitting and chunking in React ***
37. What is server-side rendering (SSR) vs client-side rendering (CSR) ***
38. What are performance optimization techniques in React (avoid re-renders, memoization, virtualization, caching) ***
39. What are controlled vs uncontrolled inputs (forms) ***
40. How does React handle events differently from browser DOM **
41. What is state lifting **
42. What is the difference between default export and named export in React **
43. Create a component rendering data with pagination. ***

---

# SCENARIO-BASED REACT QUESTIONS

### State & Rendering Scenarios
1. A component re-renders too many times — how do you find the cause and fix it? ***
2. You have a list of 10,000 items — how do you render it without freezing the UI? (virtualization) ***
3. You have deeply nested components — how do you avoid prop drilling? (Context, custom hooks, state libraries) ***
4. A state update is not reflecting immediately — why does this happen and how do you fix it? ***
5. useEffect is running in an infinite loop — what causes this? ***

### Performance Scenarios
6. A large form becomes slow — what React optimizations will you apply? ***
7. A slow API response is blocking render — how do you show fallback UI with Suspense or loaders? ***
8. How do you cache expensive calculations in React? (useMemo) ***

### API & Data Handling Scenarios
9. API fails sometimes — how do you implement retry logic? ***
10. Requirement: show global loader during all API calls — how do you implement this? ***
11. You need to cancel API requests on component unmount — how do you implement it? ***

### Architecture Scenarios
12. How will you structure a large React project? (feature-based modules, hooks, services, store) **
13. Multiple components need shared logic — how will you reuse it? (custom hooks) ***
14. Multiple components need shared global state — when to use Context vs Redux? ***

### Security & Auth Scenarios
15. Where do you store JWT tokens securely? (httpOnly cookie vs localStorage) ***
16. How to implement token refresh on 401 errors? ***
17. How to protect routes in React Router? (private routes) ***

### UI/UX Scenarios
18. How to implement skeleton loader while data loads? ***
19. A dropdown must close when clicking outside — how to implement click outside detection? ***
20. A modal must render above everything — how to implement with portals? ***

### Task
1. Create a dashboard/table after fetching data from api, should be capable of CRUD operations and search filter. ***






ORDER:-

# React Interview Prep — MERN Stack (Learning Order)

---

## Phase 1 — The Basics (Start Here)
- [ ] What is React? **
- [ ] Is React a framework? **
- [ ] What is a Single Page Application (SPA)? **
- [ ] What is JSX and why is it used in React? ***
- [ ] What are components in React and how are they useful? ***
- [ ] What is Virtual DOM? ***
- [ ] What is reconciliation in React (how React updates DOM)? ***
- [ ] What is the difference between default export and named export in React? **

---

## Phase 2 — Props, State & Components
- [ ] What are props and state (difference between them)? ***
- [ ] What is the difference between class components and functional components? ***
- [ ] What are lifecycle methods (mount/update/unmount) in class components? **
- [ ] What are keys in lists and why are they important? ***
- [ ] What are controlled and uncontrolled components? ***
- [ ] What are controlled vs uncontrolled inputs (forms)? ***
- [ ] What is state lifting? **
- [ ] What is React Fragment and why is it used? **
- [ ] What are synthetic events in React? **
- [ ] How does React handle events differently from browser DOM? **

---

## Phase 3 — React Hooks (Most Important Phase)
- [ ] What are React Hooks? ***
- [ ] Explain useState ***
- [ ] Explain useEffect ***
- [ ] Difference between useEffect and useLayoutEffect ***
- [ ] Explain useLayoutEffect ***
- [ ] Explain useRef ***
- [ ] Explain useMemo ***
- [ ] Explain useCallback ***
- [ ] What is useReducer and when to use it? **
- [ ] What are custom hooks and when to use them? ***
- [ ] Explain React.memo and how it helps in optimization ***
- [ ] What is React.StrictMode and why is it used? **

---

## Phase 4 — State Management & Data Flow
- [ ] What is prop drilling and how to avoid it? ***
- [ ] Explain Context API and how to integrate it ***
- [ ] What is Redux and Redux Toolkit? How do you create a store? ***
- [ ] How to handle state in large applications (Context, Redux, Zustand, MobX, Jotai)? ***
- [ ] How to structure a React application folder? **

---

## Phase 5 — Routing, API & Authentication
- [ ] How to route between pages in React? **
- [ ] How will you handle authentication in frontend and where to store the token? ***
- [ ] Where do you store JWT tokens securely? (httpOnly cookie vs localStorage) ***
- [ ] How to protect routes in React Router? (private routes) ***
- [ ] What are interceptors in Axios? ***
- [ ] How to implement token refresh on 401 errors? ***
- [ ] You need to cancel API requests on component unmount — how do you implement it? ***
- [ ] API fails sometimes — how do you implement retry logic? ***
- [ ] Requirement: show global loader during all API calls — how do you implement this? ***

---

## Phase 6 — Performance Optimization
- [ ] Explain React.memo and how it helps in optimization ***
- [ ] A component re-renders too many times — how do you find the cause and fix it? ***
- [ ] How to handle large number of records in a table (virtualization)? ***
- [ ] You have a list of 10,000 items — how do you render it without freezing the UI? (virtualization) ***
- [ ] What is code splitting and chunking in React? ***
- [ ] When and how to use lazy loading? ***
- [ ] What is server-side rendering (SSR) vs client-side rendering (CSR)? ***
- [ ] What are performance optimization techniques in React (avoid re-renders, memoization, virtualization, caching)? ***
- [ ] A large form becomes slow — what React optimizations will you apply? ***
- [ ] A slow API response is blocking render — how do you show fallback UI with Suspense or loaders? ***
- [ ] How do you cache expensive calculations in React? (useMemo) ***
- [ ] A state update is not reflecting immediately — why does this happen and how do you fix it? ***
- [ ] useEffect is running in an infinite loop — what causes this? ***
- [ ] You have deeply nested components — how do you avoid prop drilling? (Context, custom hooks, state libraries) ***

---

## Phase 7 — Advanced Patterns & UI
- [ ] What are error boundaries in React? ***
- [ ] What is React Portal and when to use it? **
- [ ] A modal must render above everything — how to implement with portals? ***
- [ ] What are higher-order components (HOCs)? **
- [ ] How to implement skeleton loader while data loads? ***
- [ ] A dropdown must close when clicking outside — how to implement click outside detection? ***
- [ ] Multiple components need shared logic — how will you reuse it? (custom hooks) ***
- [ ] Multiple components need shared global state — when to use Context vs Redux? ***
- [ ] How will you structure a large React project? (feature-based modules, hooks, services, store) **
- [ ] How to debug a React application? ***

---

## Phase 8 — Build Tasks (Most Asked in Interviews)
- [ ] Create a component rendering data with pagination ***
- [ ] Create a dashboard/table after fetching data from api, should be capable of CRUD operations and search filter ***
