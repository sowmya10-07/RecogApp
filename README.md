## RecogApp<br>

### Description<br>
A browser-based application which uses face recognition to display ads in a smarter way, gain customer analytics and to help the blind to understand the emotions of the person near them**.<br>

### Getting Started<br>
Link to the web-app: https://recogapp.herokuapp.com/<br>
or<br>
Follow the below instructions to run the app on local host<br>
1. Clone the git repository<br>
2. Have **Node.js** installed in your system<br>
3. In CMD, run the command **npm install http-server -g**<br>
4. Navigate to the specific path of the cloned file in CMD and run the command **http-server**
5. Go to your browser and type **localhost:8080**. Application should run there.

### App Architecture<br>
The app starts with the home page which links to<br><br>
<B>1. Smarter Advertising </B><br>
The app detects the faces near the digital advertising board, recognizes their age and gender. This information is used to display ads accordingly on the digital advertising board.<br>
<B>2. Customer Analytics</B><br>
The app captures faces of the people in a store. It shows the age and gender group visiting the store, the expressions of the people in the store. This information gives the owners better understanding of their customers and can help them better their services.<br>
<B>3. Help the Blind</B><br>

### Techstack <br>
* Face-api.js (a javacript api which is used to detect faces, recognize expressions, age and gender)
* HTML
* CSS
* Javascript
* jQuery
 
 ### References <br>
 * Using face-api.js: https://medium.com/theleanprogrammer/face-api-js-a-way-to-build-face-recognition-system-in-browser-c1f4ac922657
