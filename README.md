# lightSwitch

## 1. Room component
- Create a 'Room' component in `/src/Room.js`
- The root `div` of the component should have `className` attribute with value 'lit'
- Add a paragraph that reads 'The room is lit' 
- Add a "lightswitch" button
- Clicking the button should toggle the light on and off:
  - The text should change to 'The room is dark'
  - The class of the `div` should change to 'dark'
- Use the `useState` hook to store the lightswitch state. By default the room should be lit .

You can use the following CSS

```css
html,
body,
#root,
.room {
  height: 100vh;
  margin: 0;
  text-align: center;
  font-family: "Georgia", serif;
  font-size: 1.5rem;
}

button {
  padding: 0.25rem 0.5rem;
  font-size: 1rem;
}

.room {
  padding: 30px;
}

.lit {
  background-color: white;
  color: black;
}

.dark {
  background-color: black;
  color: white;
}

```