## Answer the following questions in the readme.md file inside your project above

#### List five significant features of React

- 1. Virtual DOM:
- 2. JSX (javaScript Syntax Extension)
- 3. One-Way Data Binding (unidirectional data flow)
- 4. Dedicated tools for easy debugging
- 5. Improved performance

#### List five major advantages of React

- 1. Short Learning Curve
- 2. Enables Building Rich UI
- 3. Facilitates Creation of Custom Components
- 4. It Boosts Developer Productivity
- 5. Quick Rendering

#### What is the name of the Software Engineer that created React? Also, which company owns React?

The software engineer is Jordan Walke. Facebook owns React.

#### What are the notable differences between HTML & JSX? Give at least 3 of them

- 1. In html attributes are written with hyphen to differentiate word example: font-size, but in JSX we use camelCase for example fontSize.
- 2. Self-closing tags in HTML can self-close without the slash before the right angle bracket, that is <br /> could work as <br>. But in JSX, you need to include the slash.
- 3. in JSX you must return a single parent element, or it won't compile but in html you are free to do whatever you want as you don’t have to return a single parent element.

#### Why can’t browsers read JSX?

Browsers cant read JSX because they can only read JavaScript objects but JSX in not a regular JavaScript object. Thus to enable a browser to read JSX, first, we need to transform JSX file into a JavaScript object using JSX transformers like Babel and then pass it to the browser.
