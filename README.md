# prince

import React from 'react'; 
import './components/A.css';
function App() { 
	return ( 
		<div> 
      <header className="header">
        <p className="text-header">
          THE MIDNIGHT LIBRARY
        </p>
      </header>
			<nav class="navbar background"> 
				<ul class="nav-list"> 
					<div class="logo"> 
					</div> 
					<li><a href="#courses">Courses</a></li> 
					<li><a href="#tutorials">Tutorials</a></li> 
					<li><a href="#jobs">Jobs</a></li> 
					<li><a href='#student'>Student</a></li> 
				</ul> 

        
        
				<div class="rightNav"> 
					<input type="text" name="search" id="search" /> 
					<button class="btn btn-sm">Search</button> 
				</div> 
			</nav> 
			<section class="section"> 
				<div class="box-main"> 
					<div class="firstHalf"> 
						<h1 class="text-big"> 
							
						</h1> 
						<p class="text-small"> 
							
						</p> 
					</div> 
				</div> 
			</section> 
			<section class="section"> 
				<div class="box-main"> 
					<div class="secondHalf"> 
						<h1 class="text-big" id="program"> 
							JavaScript Tutorial 
						</h1> 
						<p class="text-small"> 
							 JavaScript is the world most popular 
							lightweight, interpreted compiled 
							programming language.  
              It is also 
							known as scripting language for
							web pages. 
               It is well-known for
							the development of web page many 
							non-browser environments also use 
							it. . 
						</p> 
					</div> 
				</div> 
			</section> 
			<section class="section"> 
				<div class="box-main"> 
					<div class="secondHalf"> 
						<h1 class="text-big" id="program"> 
							Java Programming Language 
						</h1> 
						<p class="text-small"> 
							When compared with C++, Java codes 
							are generally more maintainable 
							because Java does not allow many 
							things which may lead to 
							bad/inefficient programming if used 
							incorrectly. For example, 
							non-primitives are always references 
							in Java.
						</p>
					</div> 
				</div> 
			</section> 
			<section class="section"> 
				<div class="box-main"> 
					<div class="secondHalf"> 
						<h1 class="text-big" id="program"> 
							What is Machine Learning? 
						</h1> 
						<p class="text-small"> 
							Machine Learning is the field of study 
							that gives computers the capability to 
							learn without being explicitly 
							programmed. ML is one of the most exciting 
							technologies that one would have ever 
							come across. The ability 
							to learn. Machine learning is actively 
							being used today, perhaps in many more 
							places than one would expect. 
						</p> 
					</div> 
				</div> 
        
			</section> 
      
			<footer className="footer"> 
				<p className="text-footer"> 
        ANY TIME LEARNING
				</p> 
			</footer> 
		</div> 
	) 
} 

export default App 





* { 
	margin: 0; 
	padding: 0; 

} 

.navbar { 
	display: flex; 
	align-items: center; 
	justify-content: center; 
	position: sticky; 
	top: 0; 
	cursor: pointer; 
} 

.background { 
    background-image: url('./library.png');
    background-repeat: repeat;
} 

.footer { 
background-color: #d83fc4; 
} 
.header {
    background-color: rgb(32, 185, 185);

}

.nav-list { 
	width: 70%; 
	display: flex; 
	align-items: center; 
} 

.logo { 
	display: flex; 
	justify-content: center; 
	align-items: center; 
} 

.logo img { 
	width: 180px; 
	border-radius: 50px; 
} 

.nav-list li { 
	list-style: none; 
	padding: 26px 30px; 
} 

.nav-list li a { 
	text-decoration: none; 
	color: #1739cf; 
} 

.nav-list li a:hover { 
	color: grey; 
} 

.rightnav { 
	width: 30%; 
	text-align: right; 
} 

#search { 
	padding: 5px; 
	font-size: 17px; 
	border: 2px solid rgb(182, 36, 36); 
	border-radius: 9px; 
} 

.box-main { 
	display: flex; 
	justify-content: center; 
	align-items: center; 
	color: rgb(3, 3, 2); 
	max-width: 80%; 
	margin: auto; 
	height: 80%; 
} 

.firsthalf { 
	width: 100%; 
	display: flex; 
	flex-direction: column; 
	justify-content: center; 
} 

.secondhalf { 
	width: 30%; 
} 

.secondhalf img { 
	width: 70%; 
	border: 4px solid white; 
	border-radius: 150px; 
	display: block; 
	margin: auto; 
} 

.text-big { 
	font-weight: 500; 
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
	font-size: 30px; 
} 

.text-small { 
	font-size: 18px; 
} 

.btn { 
margin-left: 20px; 
height: 33px; 
width: 70px; 
	color: #fff; 
background-color: #b90b0b; 
	cursor: pointer; 
} 

.btn-sm { 
	padding: 6px 10px; 
	vertical-align: middle; 
} 

.section { 
	height: 200px; 
	display: flex; 
	align-items: center; 
	background-color: rgb(250, 250, 250); 
	justify-content: space-between; 
} 

.section-Left { 
	flex-direction: row-reverse; 
} 

.center { 
	text-align: center; 
} 

.text-footer { 
	text-align: center; 
	padding: 30px 0; 
	font-family: 'Ubuntu', sans-serif; 
	display: flex; 
	justify-content: center; 
	color: #fff; 
} 
.text-header{
    text-align: center;
    padding: 30px 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    display:flex;
    justify-content: center;
}



 import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';


const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App/>
  </React.StrictMode>
);



// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals



import { BrowserRouter as Router, Switch, Route } from 'react-router-dom';

function App() {
  return (
    <Router>
      <Switch>
        <Route path="/" exact component={Home} />
        <Route path="/search/:query" component={SearchResults} />
      </Switch>
    </Router>
  );
}




import { useHistory } from 'react-router-dom';

function SearchBar() {
  const history = useHistory();

  const handleSearch = (query) => {
    history.push(`/search/${query}`);
  };

  return (
    <form onSubmit={(e) => {e.preventDefault(); handleSearch(query)}}>
      <input type="text" value={query} onChange={(e) => setQuery(e.target.value)} />
      <button type="submit">Search</button>
    </form>
  );
}
