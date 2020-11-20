### Notes

https://frontendmasters.com/courses/complete-react-v5/setting-state-with-hooks/

https://github.com/btholt/complete-intro-to-react-v5

(skipped until **Creating a Search Component**)

ErrorBoundaries are only available in class components.

React will not deprecate class components, so your application can be a mix of functional and class components.

**Context** is a way to manage global state in your application, e.g. user login data. Otherwise, we'd have to pass it down to each component in our app, which is known as `prop drilling`. 

**Redux** has historically been used. It's more complicated than **Context**, but will be covered in in intermediate courses.

Context with class components is a bit strange

Although we cover modals, the presenter believes they are a lazy design pattern and annoying, like alerts. Instead, we could try inline confirmation, or something else more conspicuous.

Checkout `modal.js`, `index.html` and `details.js` for demo on using modals!