# examples_codepen

Simple Hello world:
function Welcome(props){
 return <h1> Hello All !</h1>
};

//const element = <Welcome />
      
 ReactDOM.render(<Welcome/>, document.getElementById('root'));

------------------
Generating Array:
const numbers = [2,4,6,8,10];
const doubled = numbers.map((number) => <li>{number} </li>)
                            
const ele = <ul> {doubled} </ul>

ReactDOM.render(ele,
document.getElementById('root')
);
-------------------
