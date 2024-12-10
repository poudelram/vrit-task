# vrit-task
## Technology Choices and Rationale

- **HTML/CSS**: Used for creating the structure and design of the UI, including responsive layouts.
- **Vanilla JavaScript**: Provides the logic for smooth transitions and card navigation without requiring external libraries.
- **Browser Native Events**: Utilizes the `wheel` event for lightweight and efficient scrolling interactions.

The rationale for these choices is to keep the project simple and lightweight while showcasing fundamental web development skills.

## Known Limitations/Trade-offs

- **Limited Accessibility**: The current design doesn't include keyboard navigation or screen reader support.
- **Scroll-based Navigation**: Users relying on touch devices may find navigation challenging.
- **No Persistent State**: Card states reset on page reload since there's no state management or backend integration.

## Future Improvements

1. **Accessibility Enhancements**:
   - Add keyboard navigation and focus management.
   - Improve screen reader compatibility.

2. **Touch Support**:
   - Implement swipe gestures for better usability on mobile devices.

3. **Persistent State**:
   - Use `localStorage` or a backend to remember the last viewed card.

4. **Styling**:
   - Add more customization options for themes and transitions.

5. **Dynamic Cards**:
   - Allow users to add, remove, or edit cards dynamically.
