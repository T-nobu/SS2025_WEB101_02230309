# Practical 6: State Management (Todo List with Zustand) Reflection 📝

## What I Learned

### Zustand Basics
- Zustand makes state management super simple — no providers or boilerplate like Redux.
- It keeps state and actions together, making the code clean and easy to manage.
- Using selectors helps components only re-render when needed, boosting performance.

### React & Zustand Together
- Combined Zustand’s global state with React’s local state (`useState`) for input handling.
- Persistence with `persist` middleware saved todos automatically in localStorage — no extra setup needed.

### Components & Structure
- Built focused components (`TodoInput`, `TodoItem`, `TodoList`) each handling one responsibility.
- Passed todo data as props but got actions directly from the store for better modularity.

## Challenges & Solutions

- **Too many re-renders?**  
  Initially subscribed to the whole store, causing excess re-renders. Fixed by selecting only needed parts of the state.

- **Persistence confusion:**  
  Struggled with configuring persistence at first, but Zustand’s middleware made it easy once set up correctly.

- **Immutable updates:**  
  Learned the hard way to never mutate state directly. Always create new arrays/objects to update state.

- **Props vs global state:**  
  Found a good balance by passing data as props but accessing actions via the store.

## Key Takeaways

- Zustand offers a great developer experience — simple, fast, with excellent debugging tools.
- It’s lightweight and performs well, ideal for small to medium apps.
- For bigger apps, splitting stores and using middleware can keep things organized.

## How It Compares

- **Vs Context API:** Easier to use, better performance, no provider nesting.
- **Vs Redux:** Much less code, simpler learning curve, built-in persistence.

## What’s Next?

- Add features like tags, due dates, filters.
- Improve with TypeScript, tests, and backend sync.
- Enhance UX with drag-and-drop and undo.

## Final Thoughts

This project showed me how powerful and simple Zustand is for React state management. It strikes a perfect balance — easy enough for small projects but powerful enough to scale. Definitely a tool I’ll use more going forward!
