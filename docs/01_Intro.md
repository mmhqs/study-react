⚛️ **What is React?**
----------------------------------
- A Javascript library.
- Easy to learn, simple design, flexible (easily to integrate with other libraries), fast. We spend more time worrying with modern Javascript than understanding its structures. 
- It has a virtual DOM. The browser DOM only render what was modified.
- It works with JSX, which is a syntax extension for Javascript. It looks like Javascript mixed with HTML. Example:
  `const elemento = <h1>Bom dia!</h1>;`
- To use Javascript in JSX syntax, you can use {}. After compiling, JSX calls become regular Javascript function calls.
- "class" in HTML becomes "className" in JSX. "onclick" in HTML becomes "onClick" in JSX. It uses cammel case.
- Other frameworks: Angular and Vue.

:1st_place_medal: **Why is React so relevant?**
----------------------------------
- The difference between SSR x SPA
1) **Server Side Rendering**:
    - Traditional applications that are rendered on servers.
    - Based on static book pages.
    - One server request per URL page.
    - Direct DOM manipulation.
    - State management per page.

2) **Single Page Application**
    - React applications.
    - Based on components.
    - Javascript will generate pages.
    - One request.
    - DOM is updated automatically.
    - State management per component.

🍰 **What is a component?**
----------------------------------
- It allows you to split the user inteface in independent and reusable parts.
- It allows you to think about each part separately.

🤯 **Props x state**
----------------------------------
- Imagine the component as a simple function. The props are the parameters and the DOM rendering is the output.
- Props can't be altered by the components!
- The state belongs to the component, it's in the component scope. States can be altered!

PROPS > COMPONENTS (STATE) > DOM

🫲 **React project anatomy**
----------------------------------
- package.json: dependencies, project settings (project name, version, description, keywords etc), scripts, browsers list and others.
- index.html: standard page with the tag <link> "manifest" and "shorcut".
- index.js: it will start the app.

:brain: **Things to remember**
----------------------------------
- A component is a function.
- We can render components inside components.
- Everything that's inside {} are Javascript variables.
- React components have props (or properties) that are inputed as parameters. Example: property "title". When a component receives a prop, it actually receives an object as parameter.
