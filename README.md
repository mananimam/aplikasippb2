# aplikasippb2
================
File index.js
//==========
// Vidio 4
//==========
//import React from 'react';
//import ReactDOM from 'react-dom';
//import './index.css';
//import reportWebVitals from './reportWebVitals';
//const HelloWorld = () => {
//   return <p>Hello React!</p>
//}

//ReactDOM.render(<HelloWorld />, document.getElementById('root'));
//ReactDOM.render(<p>Hello Sam boss</p>, document.getElementById('root'));

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
//reportWebVitals();

//==========
// Vidio 5
//==========
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import reportWebVitals from './reportWebVitals';
import Hello from './component/HelloComponent';
import HelloFull from './container/StateFullComponent';
import youtubecomp from './component/youtubecomponent/youtubecomp';

//===========
//Function
//===========
//function HelloComponent(){
//    return <p>Iki Piye Sam</p>
//}

//===========
//Class
//===========
//const HelloComponent = () => {
//    return <p>Iki Piye Sam</p>
//}

//class StateFullComponent extends React.Component{
//    render(){
//        return <p>Iki State Full Component</p>    }
//}

//=================
//Class per Folder
//=================


ReactDOM.render(<youtubecomp />, document.getElementById('root'));


// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();

=================
Hellocomponent.jsx
=================
import React from 'react';
import './Hellocomponent.css';

const Hello = () => {
    return <p className="text-p">Hello Sam</p>
}
export default Hello;

=================
Hellocomponent.css
=================
.text.p {
    color:rgb(43, 129, 199);
}

=================
StateFullComponent.jsx
=================
import React from 'react';

class HelloFull extends React.Component {
render (){
    return <p>Hello Sam</p>
}

}
export default HelloFull;

=================
youtubecomp.jsx
=================
import React from 'react';
import './youtubecomp.css';
const youtubecomp = () => {
    return (
        <div className="youtube-wrapper">
            <div className="img-thumb">
                <img src= "http://cdnwp.s3-id-jkt-1.kilatstorage.id/home/imam/wp/wordpress/wp-content/paymentreceipt_140895_1.png" alt=""/>
                <p className="time">7.12</p>
            </div>
        <p>Image Thumb Hare</p>
        <p>Title Hare</p>
        <p>Desc Hare</p>
        </div>
    ) 
}
export default youtubecomp;
========================
Stuck di Vidio 6 nggak bisa tampil untuk youtubecompnya.
Lagi dicari belum nemu 
========================
