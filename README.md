# codigo-livre-2023
codigo-livre

.md-stepper-horizontal {
	display:table;
	width:100%;
	margin:0 auto;
	background-color:#FFFFFF;
	//box-shadow: 0 3px 8px -6px rgba(0,0,0,.50);
}
.content {
	width:100%;
	margin:0 auto;
	background-color:#FFFFFF;
	//box-shadow: 0 3px 8px -6px rgba(0,0,0,.50);
}
.md-stepper-horizontal .md-step {
	display:table-cell;
	position:relative;
	padding:24px;
}
.md-stepper-horizontal .md-step:hover,
.md-stepper-horizontal .md-step:active {
	background-color:rgba(0,0,0,0.04);
}
.md-stepper-horizontal .md-step:active {
	border-radius: 15% / 75%;
}
.md-stepper-horizontal .md-step:first-child:active {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}
.md-stepper-horizontal .md-step:last-child:active {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}
.md-stepper-horizontal .md-step:hover .md-step-circle {
	background-color:#757575;
}
.md-stepper-horizontal .md-step:first-child .md-step-bar-left,
.md-stepper-horizontal .md-step:last-child .md-step-bar-right {
	display:none;
}
.md-stepper-horizontal .md-step .md-step-circle {
	width:30px;
	height:30px;
	margin:0 auto;
	background-color:#999999;
	border-radius: 50%;
	text-align: center;
	line-height:30px;
	font-size: 16px;
	font-weight: 600;
	color:#FFFFFF;
}
.md-stepper-horizontal .md-step.active .md-step-circle {
	background-color:#00AE4D;
}
.md-stepper-horizontal .md-step.done .md-step-circle:before {
	font-family:'FontAwesome';
	font-weight:100;
	content: "\2714";
}
.md-stepper-horizontal .md-step.done .md-step-circle *,
.md-stepper-horizontal .md-step.editable .md-step-circle * {
	display:none;
}
.md-stepper-horizontal .md-step.editable .md-step-circle {
	-moz-transform: scaleX(-1);
	-o-transform: scaleX(-1);
	-webkit-transform: scaleX(-1);
	transform: scaleX(-1);
}
.md-stepper-horizontal .md-step.editable .md-step-circle:before {
	font-family:'FontAwesome';
	font-weight:100;
	content: "\f040";
}
.md-stepper-horizontal .md-step .md-step-title {
	font-size:16px;
	font-weight:600;
}
.md-stepper-horizontal .md-step .md-step-title,
.md-stepper-horizontal .md-step .md-step-optional {
	text-align: center;
	color:rgba(0,0,0,.26);
}
.md-stepper-horizontal .md-step.active .md-step-title {
	font-weight: 600;
	color:rgba(0,0,0,.87);
}
.md-stepper-horizontal .md-step.active.done .md-step-title,
.md-stepper-horizontal .md-step.active.editable .md-step-title {
	font-weight:600;
}
.md-stepper-horizontal .md-step .md-step-optional {
	font-size:12px;
}
.md-stepper-horizontal .md-step.active .md-step-optional {
	color:rgba(0,0,0,.54);
}

.md-stepper-horizontal .md-step .md-step-bar-left,
.md-stepper-horizontal .md-step .md-step-bar-right{
	position:absolute;
	top:93px;
	height:1px;
	border-top:3px solid #b9bdba;
}
.md-stepper-horizontal .md-step .md-step-bar-left:active,
.md-stepper-horizontal .md-step .md-step-bar-right:active{
	border-top:3px solid #0ab435;
}
.md-stepper-horizontal .md-step .md-step-bar-left.active,
.md-stepper-horizontal .md-step .md-step-bar-right.active{
	border-top:3px solid #0ab435;
}
.md-stepper-horizontal .md-step .md-step-bar-right {
	right:0;
	left:48%;
}
.md-stepper-horizontal .md-step .md-step-bar-left {
	left:0;
	right:48%;
}

<div class="md-stepper-horizontal">
  <div class="md-step active done">
    <div class="md-step-title">parecer</div>
    <div class="md-step-circle"><span>1</span></div>
    <div class="md-step-bar-right active"></div>
  </div>
  <div class="md-step active">
    <div class="md-step-title">desisão</div>
    <div class="md-step-circle"><span>2</span></div>
    <div class="md-step-bar-left active"></div>
    <div class="md-step-bar-right"></div>
  </div>
  <div class="md-step">
    <div class="md-step-title">revisão</div>
    <div class="md-step-circle"><span>3</span></div>
    <div class="md-step-bar-left"></div>
    <div class="md-step-bar-right"></div>
  </div>
</div>
