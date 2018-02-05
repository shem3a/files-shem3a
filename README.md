body{
	margin:5;
	background:#2f323b;
	background-size: cover;
	background-repeat: no-repeat;
}
/*Header*/
header{
	color:white;
}
.title{
  text-align: center;
	font-family: "GeosansLight";
	text-shadow: 5px 0px 25px #03DCF9;
	font-size: 3rem;
	padding: 20px;

}

/*Body Principal*/
.title img{

	display: inline-block;
	height: 2.5rem;
	vertical-align: middle;
}

.hh-title {
  text-align: center;
	font-family: "Orbitron";
	font-size: 10;
}

/*Inputs*/
form#console {
	text-align: center;
}
.Ilabel, .input_text,.input_texts {
	display: -webkit-inline-box;
	font-family: 'GeosansLight';
	font-size: 19px;
}
.Ilabel {
	background-color: #4d4f53;
	padding: 5px;
	border-radius: 5px 0 0 5px;
	border-bottom: 2px #00FFFF;
	color: white;
}
.input_text {
	padding: 6px;
	border: 0;
	border-bottom: 2px solid #00FFFF;
	border-right: 2px solid #00FFFF;
	border-radius: 0 5px 5px 0;
	vertical-align: bottom;
	outline: none;
	font-size:20px;
}
select.input_text {
	margin-left: -5px;
	font-size: 16px;
	background: white;
}
.p {
	display: -webkit-inline-box;
	margin-bottom: 12px;
}
.s{
	margin-left: -5px;
	background: white;
	padding: 5.5px;
}
.input_text>label{
	cursor:pointer;
}
.clean{
	background: rgba(0, 128, 128, 0.83) url('../img/close_white.png') 0 0 no-repeat;
	border-radius: 50%;
	cursor: pointer;
	height: 24px;
	width: 24px;
	float: right;
	margin: 0 -12px -12px 0;
	position: relative;
	transition: all 0.5s;
	-webkit-transition: all .5s;
}
.clean:hover {
	background: rgba(0, 128, 45, 0.87) url('../img/close_white.png') 0 0 no-repeat;
	-webkit-transform: rotate(360deg);
	transform: rotate(360deg);
}
.cleanit{
	background: rgba(206, 52, 52, 0.87) url('../img/close_white.png') 0 0 no-repeat;
	border-radius: 50%;
	cursor: pointer;
	height: 24px;
	width: 24px;
	float: right;
	position: relative;
	transition: all 0.5s;
	-webkit-transition: all .5s;
}
.cleanit:hover {
	background: rgba(0, 0, 0, 0.87) url('../img/close_white.png') 0 0 no-repeat;
	-webkit-transform: rotate(360deg);
	transform: rotate(360deg);
}
.eighty{
	width:80%;
}

/*Boton*/
.Lbutton {
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #ffffff), color-stop(1, #f6f6f6));
	background:-moz-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:-webkit-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:-o-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:-ms-linear-gradient(top, #ffffff 5%, #f6f6f6 100%);
	background:linear-gradient(to bottom, #ffffff 5%, #f6f6f6 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffffff', endColorstr='#f6f6f6',GradientType=0);
	background-color:#ffffff;
	-moz-border-radius:6px;
	-webkit-border-radius:6px;
	border-radius:6px;
	border:1px solid #00FFFF;
	display:inline-block;
	cursor:pointer;
	color:#2D7681;
	font-family:Courier New;
	font-size:20px;
	font-weight:bold;
	padding:8px 40px;
	text-decoration:none;
}
.Lbutton:hover {
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #f6f6f6), color-stop(1, #ffffff));
	background:-moz-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:-webkit-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:-o-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:-ms-linear-gradient(top, #f6f6f6 5%, #ffffff 100%);
	background:linear-gradient(to bottom, #f6f6f6 5%, #ffffff 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#f6f6f6', endColorstr='#ffffff',GradientType=0);
	background-color:#f6f6f6;
}
.Lbutton:active {
	position:relative;
	top:1px;
}

/*Textarea*/
.textarea {
	border-bottom: 2px solid #00FF73;
	border-top: 2px solid #00FFFF;
	border-left: 0;
	border-right: 0;
	width: 100%;
	font-size: 16px;
	margin-bottom: 10px;
	outline: none;
	font-family: 'GeosansLight';
	overflow-x: hidden;
	overflow-y: scroll;
}
.textarea::-webkit-scrollbar {
	width: 10px;
}
.textarea::-webkit-scrollbar-thumb {
	background: #008080 !important;
}

/*Footer*/
footer {
	background: #2b2e2f;
	border-top: 5px solid 2b2e2f;
	text-align: center;
	font-family: 'UbuntuRegular';
	color: white;
	padding: 5px;
	font-size: 15px;
}

/*Ajustar*/
@media (max-width: 376px){
	.title{
		font-size: 1.5rem;
	}
	.p{

	}
	.Ilabel{
		width: 90%;
		border-radius: 0;
	}
	.input_text{
		width: 80%;
		border-radius: 0;
		text-align: -webkit-center;
		border-right: 0;
	}
	.inline{
		width: 40%;
	}
	.hh{
		text-align: center;
	}
}
@media (max-width: 595px){
	.form{
		width:99%;
		margin: 5px 0 5px 0;
	}
}
@media (max-width: 445px){
	.item{
		width:38%;
	}
}
@media (max-width: 745px){
	.z1,.z2,.z3,.z4,.z5,.z7{
		width:100%;
	}
	.y{
		display:none;
	}
	.z1{
		background: teal;
		color: white;
	}
}
@media (max-width: 1016px){
	.menu,.principal{
		width:100%;
	}
	#a0{
		display:block;
	}
	#menu-sub{
		display:none;
	}
	.item-title{
		font-size: 20px;
	}
}
@media (min-width: 1017px){
	#menu-sub{
		display:block !important;
	}
}
