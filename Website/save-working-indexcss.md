body {
font-family: "Kanit", sans-serif;
}
/_ TOPP NAV START(SPELLING ERROR INTENDED) _/
img {
width: 100px; /_ width of container _/
height: 100px; /_ height of container _/
overflow: hidden;
border: 5px solid black;
}

img:hover {
box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}

.nav-list {
background-color: white;
/_ box-shadow: 0px 0px 10px; _/
margin: 0;
padding: 1rem 0;
border-radius: 20px;
display: flex;
justify-content: flex-start;
align-items: center;
}

.nav-item {
list-style: none;
margin-right: 2rem;
}

.nav-item a {
text-decoration: none;
color: black;
transition: all 200ms ease-in;
}

.nav-item a:hover {
color: green;
}

.nav-item:first-child {
}

.button-login {
border: none;
outline: none;
border-radius: 3px;
background-color: green;
font-size: 20px;
cursor: pointer;
transition: all 200ms ease-in;
font-family: "Kanit", sans-serif;
float: right;
}

.button-login:hover {
color: white;
}

.nav-list:first-child {
font-size: 20px;
}

/_ TOPP NAV DONE (SPELLING ERROR INTENDED) _/
/_ TOP NAV START _/
.topnav {
overflow: hidden;
background-color: #333;
}

.topnav a {
float: left;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
font-size: 17px;
}

.topnav a:hover {
background-color: #ddd;
color: black;
}

.topnav a.active {
background-color: #04aa6d;
color: white;
}

/_-_/
.sticky {
position: fixed;
top: 0;
width: 100%;
}

/_ TOP NAV DONE _/
/_ SIDE BAR START _/
.sidenav {
height: 100%;
width: 200px;
position: fixed;
z-index: 1;
top: 0;
left: 0;
background-color: #cacaca;
overflow-x: hidden;
padding-top: 20px;
}
/_//#111_/

.sidenav a {
padding: 6px 8px 6px 16px;
text-decoration: none;
font-size: 20px;
color: black; /_#818181_/
display: block;
}

.sidenav:first-child {
color: white;
font-size: 25px;
}

.sidenav a:hover {
color: #f1f1f1;
}

.everything {
margin-left: 200px; /_ Same as the width of the sidenav _/
font-size: 28px; /_ Increased text to enable scrolling _/
padding: 0px 10px;
}

@media screen and (max-height: 450px) {
.sidenav {
padding-top: 15px;
}
.sidenav a {
font-size: 18px;
}
}

.Title {
text-decoration: underline;
}
/_ SIDE BAR END _/
.taglist {
display: flex;
flex-direction: column;
}
.taglist a {
background-color: grey;
border-radius: 20px;
padding-top: 2px;
margin: 20px;
text-align: center;
}
