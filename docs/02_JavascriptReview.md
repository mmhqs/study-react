## Javascript review

Summary
----------------------------------------
1) Variable declaration (let and const)
2) Arrow functions
3) Modules - import and export
4) Classes, properties and methods
5) Spread an rest operators
6) Destructuring assignment

Variable declaration (let and const)
----------------------------------------
- Let allows you to modify the variable.
- Const = constants.

Arrow functions
----------------------------------------
- Traditional functions:

function ola(){   
return 'Olá!'  
}
- Arrow functions:

const olaPessoa3 = nome => `Olá novamente, ${nome}!`

Modules - import and export
----------------------------------------
- It is posible to export modules from one file and import them into another file. Example:

`export default function` (in the exporting file)  
`import variable from './exporting-file/funcion.mjs'` (in the importing file)

- You can also export the functions with their names:

`export { function1 }`

Classes, properties and methods
----------------------------------------
- Objected oriented programming.

Spread an rest operators
----------------------------------------
- The spread operator is used to clone info into new objects.
- Spread and rest operators: ....

Destructuring assignment
----------------------------------------
- To get only what you need from a object.
- Instead of assigning the whole object, you can assign only what you need from it.
