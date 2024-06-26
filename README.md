

* {
    padding: 0;
    margin: 0;
}

ul,
ol {
    list-style: none;
}

a,
a:hover,
a:focus {
    text-decoration: none;
    outline: 0;
}

input:focus,
button:focus,
text-area:focus {
    outline: 0;
}

.clr {
    clear: both;
}

p {
    line-height: 24px;
    font-size: 17px;
}

body {
    font-family: 'Roboto', sans-serif;
}

body::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
    background-color: #444444;
}

body::-webkit-scrollbar {
    width: 8px;
}

body::-webkit-scrollbar-thumb {
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, .3);
    background-color: #147e90;
}

.bg-common {
    background: #147e90;
}

.bg-faded {
    background: #f7f7f7;
}

.bg-faded-two {
    background: #f2f2f2;
}

.bg-mark {
    background: #ffe9ab;
}

.color-common {
    color: #147e90;
}
h1.color-w{
    color: white;
    font-weight: 700;
}
.color-w{
    color: white;
}

.mt-6 {
    margin-top: 60px;
}

.sec-pad {
    padding: 60px 0;
}

.sec-pad-two {
    padding: 100px 0;
}

.sec-head-size {
    font-size: 32px;
    margin-top: -6px
}

.head-line {
    width: 30px;
    height: 2px;
    background: #fec600;
    position: relative;
    left: 50%;
    margin-top: 5px;
    -webkit-transform: translateX(-50%);
    -moz-transform: translateX(-50%);
    -ms-transform: translateX(-50%);
    -o-transform: translateX(-50%);
    transform: translateX(-50%);
}

.head-line:after {
    position: absolute;
    top: 0;
    right: 35px;
    content: '';
    width: 15px;
    height: 2px;
    background: #fff;
}

.head-line:before {
    position: absolute;
    top: 0;
    left: 35px;
    content: '';
    width: 15px;
    height: 2px;
    background: #fff;
}

.head-line-two {
    width: 30px;
    height: 2px;
    background: #147e90;
    position: relative;
    left: 50%;
    margin-top: 5px;
    -webkit-transform: translateX(-50%);
    -moz-transform: translateX(-50%);
    -ms-transform: translateX(-50%);
    -o-transform: translateX(-50%);
    transform: translateX(-50%);
}

.head-line-two:after {
    position: absolute;
    top: 0;
    right: 35px;
    content: '';
    width: 15px;
    height: 2px;
    background: #444444;
}

.head-line-two:before {
    position: absolute;
    top: 0;
    left: 35px;
    content: '';
    width: 15px;
    height: 2px;
    background: #444444;
}

.thin {
    font-weight: 300;
}

/**** common css here ****/

/**** fonts here ****/

.navbar-light .navbar-toggler-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 1)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-toggler {
    color: rgba(0, 0, 0, .5);
    border-color: rgba(0, 0, 0, 0);
}

header {
    position: absolute;
    top: 0;
    z-index: 9999;
    -webkit-transition: all linear 0.3s;
    -moz-transition: all linear 0.3s;
    -ms-transition: all linear 0.3s;
    -o-transition: all linear 0.3s;
    transition: all linear 0.3s;
}

header.navbar-fixed {
    position: fixed;
    top: 0px;
    left: 0px;
    z-index: 999;
    background: rgba(20, 126, 144, 0.9);
    -webkit-box-shadow: 0px 3px 7px 0px rgba(0, 0, 0, 0.30);
    -moz-box-shadow: 0px 3px 7px 0px rgba(0, 0, 0, 0.30);
    -ms-box-shadow: 0px 3px 7px 0px rgba(0, 0, 0, 0.30);
    -o-box-shadow: 0px 3px 7px 0px rgba(0, 0, 0, 0.30);
    box-shadow: 0px 3px 7px 0px rgba(0, 0, 0, 0.30);
}

header .navbar .navbar-brand {
    padding: 30px 0;
    transition: all linear 0.4s;
    -webkit-transition: all linear 0.3s;
    -moz-transition: all linear 0.3s;
    -ms-transition: all linear 0.3s;
    -o-transition: all linear 0.3s;
}

header.navbar-fixed .navbar .navbar-brand img {
    width: 50px;
}

header.navbar-fixed .navbar .navbar-brand {
    padding: 5px 0;
}

header .navbar-light .navbar-nav .nav-link {
    color: #fff;
    font-size: 20px;
    padding: 0 15px;
    position: relative;
    -webkit-transition: all linear 0.2s;
    -moz-transition: all linear 0.2s;
    -ms-transition: all linear 0.2s;
    -o-transition: all linear 0.2s;
    transition: all linear 0.2s;
}

.navbar-light .navbar-nav .nav-link:focus,
.navbar-light .navbar-nav .nav-link:hover {
    color: #fff;
}

header .navbar-light .navbar-nav .nav-link:after {
    position: absolute;
    top: 120%;
    left: 50%;
    content: url(../images/menu-hover.png);
    -webkit-user-select: none;
    -moz-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    -o-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    opacity: 0;
    -webkit-transition: all linear 0.2s;
    -moz-transition: all linear 0.2s;
    -ms-transition: all linear 0.2s;
    -o-transition: all linear 0.2s;
    transition: all linear 0.2s;
}

header .navbar-light .navbar-nav .nav-link:hover:after,
header .navbar-light .navbar-nav .nav-link.active:after {
    opacity: 1;
    top: 100%;
}

header .navbar-light .navbar-nav .nav-link.active {
    color: #fff;
}

/**** header section css ends here ****/

#general{
    background: url(../images/Web-design.jpg) no-repeat center;
    position: relative;
    padding-top: 100px;
}
#general hr {
    border-top: 2px solid rgba(236, 236, 236, 0.80);
}
#general p {
    padding-bottom: 90px;
}
.genarel-bg{
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    -webkit-background: rgba(0, 0, 0, 0) linear-gradient(to right, #ff8000 0%, #013990 100%) repeat scroll 0 0;
    -moz-background: rgba(0, 0, 0, 0) linear-gradient(to right, #ff8000 0%, #013990 100%) repeat scroll 0 0;
    background: rgba(0, 0, 0, 0) linear-gradient(to right, #ff8000 0%, #013990 100%) repeat scroll 0 0;
    opacity: 0.9;
}
.color-2{
    color: #fff;
    padding: 15px 0px;
    background: #ff8000;
}
.color-1{
    color: #fff;
    padding: 15px 0px;
    background: #013990;
}
#bannar {
    background: url(../images/demo.png)center no-repeat;
    background-size: cover;
}

#bannar .overlay {
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.0);
    padding: 200px 0 200px 0;
}

#bannar h2 {
    font-size: 30px;
    padding: 50px 0 50px 0;
    font-weight: 300
}

#bannar h2 span {
    font-weight: 400;
}

#bannar p a {
    font-size: 18px;
    font-weight: 400;
    line-height: 28px;
    color: #fff;
    border: 1px solid #fff;
    padding: 15px 30px;
    border-radius: 4px;
    -webkit-transition: all linear 0.3s;
    -moz-transition: all linear 0.3s;
    -ms-transition: all linear 0.3s;
    -o-transition: all linear 0.3s;
    transition: all linear 0.3s;
}

#bannar p a:hover {
    background: rgba(20, 126, 144, 0.6);
    color: #fff;
    border: 1px solid rgba(20, 126, 144, 0.6);
}

#bannar .social {
    margin-top: 60px;
}

#bannar .social li a i {
    color: #fff;
    margin: 0 10px;
    font-size: 16px;
    -webkit-transition: all linear 0.3s;
    -moz-transition: all linear 0.3s;
    -ms-transition: all linear 0.3s;
    -o-transition: all linear 0.3s;
    transition: all linear 0.3s;
}

#bannar .social li a i:hover {
    color: #147e90;
}

/**** bannar section css ends here ****/

#demos .demo-img{
	transition: all linear 0.3s;
}
#demos .demo-img img{
	-webkit-transition: all linear .3s;
	-moz-transition: all linear .3s;
	transition: all linear .3s;
}
/* #demos .demo-img:hover img{
	transform: translateY(calc(-100% + 300px));
	
} */

/**** demo section css ends here ****/

#feature .feature-box h5 {
    font-size: 17px;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-weight: 400;
}

#feature .feature-box h5 i {
    font-size: 23px;
}

#feature .feature-box p {
    font-size: 15px;
    color: #777777;
}

#feature .feature-list ul li {
    list-style: disc;
    margin-left: 20px;
}

/**** features section css ends here ****/

#included .file-tree {
    background: #f2f2f2;
    padding: 30px 50px;
}

#included .file-tree p {
    font-size: 16px;
    color: #444;
    margin-bottom: 3px;
}

#included .file-tree details summary {
    display: contents;
    outline: 0;
}

#included .file-tree details[open] summary ~ * {
    animation: sweep .3s ease-in-out;
}
summary::-webkit-details-marker {
  display: none
}

@keyframes sweep {
    0% {
        opacity: 0;
        padding-left: 20px;
    }
    100% {
        opacity: 1;
        padding-left: 0px;
    }
}



/**** included section css ends here ****/

#started .started-box h6 {
    font-size: 22px;
}

#started .started-box p {
    font-size: 16px;
}

.carousel-control-prev-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='dimgrey' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
}

.carousel-control-next-icon {
    background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='dimgrey' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
}

/**** started section css ends here ****/

#credits .heading-link:hover {
    color: #147e90
}

/**** testimonial section css ends here ****/

footer {
    background: #f5f5f5;
}

footer .container {
    position: relative;
    padding: 30px 0;
}

footer .container .up a i {
    position: absolute;
    top: -21px;
    right: 0;
    width: 35px;
    height: 35px;
    line-height: 21px;
    text-align: center;
    background: #f5f5f5;
    border-radius: 50%;
    font-size: 25px;
}

footer .container .up a i {
    color: #5a5a5a
}

footer .container .up a i:hover {
    color: #363636
}

.nicescroll-cursors{
    border: 0!important;
    background: #147e90!important;
}

/*all css ends here*/

.item:hover img{
transform: scale(1.05);
}# fwd1
fwd code
