## Generate a new React project with Typescript support built in
# terminal cmd: npx create-react-app <appname> --template typescript
## If your file will contain a React component or any kind of the JSX, then we use the extension '.tsx'
## If file does not contain JSX, use '.ts' 
## Passing down props from Parent to Child
### We will be utilizing Inferaces to define what props Child expects to receive 
#### Interfaces will check 1) Are we providing the correct props to Child when we show it in Parent? 2) Are we using teh correctly names + typed props in Child?
## All React Components can optionally provide these properties: 1) propTyes 2) displayName 3) defaultProps 4) contextTypes 
### *Do note Typescript doesn't know that we are making a React Component, so it thinks that 'Child' will not have these properties!
#####
## export const Child: React.FC<ChildProps> = ({color}) => {}
### above is syntax for a specific React Function Component
### Which means there may be additional componenents assigned to it.
### 'Child' might have properties assigned to it like 'propTypes' and 'contextTypes'
### 'Child' will receive props of type 'ChildProps' 
