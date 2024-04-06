 ****TOPIC: Fragments****

-Allows grouping of multiple elements without extra DOM node.
-Means in APP.jsx file we were wrapping all our components inside a parent container <div></div>, so fragments are here to return multiple elements without a wrapping parent.

**SYNTAX**
**1. import React from "react";
import "./App.css";

function App() {
  return (
  <React.Fragment>
  <h1>Healthy Food</h1>
    <ul>
      <li className="list-group-item">Pulses</li>
      <li className="list-group-item">Vegetables</li>
     
     </ul>
    
    
  </React.Fragment>
  );
}

export default App;**

2.
import React from "react";
import "./App.css";

function App() {
  return (
  <> // ********* Here we just using this******//
  <h1>Healthy Food</h1>
    <ul>
      <li className="list-group-item">Pulses</li>
      <li className="list-group-item">Vegetables</li>
      <li className="list-group-item">A third item</li>
      <li className="list-group-item">Milk And Proteins</li>
      <li className="list-group-item">A fifth item</li>
     </ul>
    
    
  </>
  );
}

export default App;


**MAP Method**
-Render lists from array data


Conditional Rendering


