<html>
  <head>
    <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Lato:400,700" rel="stylesheet">

    <link rel="stylesheet" href="../site/site.css" />
    <style>
      body {
        overflow-x: hidden;
      }
      section {
        width: 100%;
        height: 100%;
        overflow: hidden;
        position: relative;
        display: block;
        box-sizing: border-box;
        white-space: nowrap;
      }
      section > * {
        z-index: 9;
        position: relative;
        top: 0;
      }
      section > canvas {
        z-index: 1;
        position: absolute;
        left: 0;
      }
		@-webkit-keyframes rainbow{
		0%{color: orange;}	
		10%{color: purple;}	
		20%{color: red;}
		40%{color: yellow;}
		60%{color: green;}
		100%{color: blue;}
		100%{color: orange;}	
	}
	
		.rainbow {
  
   /* Font options */
  text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
  
   /* Chrome, Safari, Opera */
  -webkit-animation: rainbow 1s infinite; 
  
  /* Internet Explorer */
  -ms-animation: rainbow 3s infinite;
  
  /* Standar Syntax */
  animation: rainbow 1s infinite; 
}
      .spacing {
        width: 100%;
        min-height: 20%;
        background: -moz-linear-gradient(-45deg, #1f6bd3 0%, #2c44c9 100%);
        background: -webkit-linear-gradient(-45deg, #1f6bd3 0%, #2c44c9 100%);
        background: linear-gradient(135deg, #1f6bd3 0%, #2c44c9 100%);
        background: linear-gradient(to right bottom,#2c44c9,#2c44c9,#5955bd,#8280ce);
        background: -webkit-linear-gradient(to right bottom,#2c44c9,#2c44c9,#5955bd,#8280ce);
      }
	h1{
		position: fixed;
		top:275px;
		font-size:300px;
		left:500px;
	  }
	  
	  h2{
		top: 50px;
		position: fixed;
		font-size:100px;
		left:85;
	  }
      a {
        position: fixed;
        right: 15px;
        top: 15px;
        z-index: 99;
        border: none;
      }
      img {
		top:200px;
		width:412px;
		height:600px;
		position:fixed;
		left: 50px;
      }
    </style>
  </head>
  <body>



    <section class="example-2">
      <div class="content" style="padding:25% 0;text-align: center;">
		<img src="../examples/face.svg">
		<h2 class="rainbow">IT'S YOUR BIRTHDAY!</h2>
		<h1 class="rainbow">30<sup>th</sup></h1>
      </div>
      <canvas id="canvas2"></canvas>
    </section>

    <!-- Importing generator -->
    <script type="text/javascript" src="../dist/index.min.js"></script>
    <!-- Starting site logic -->
    <script type="text/javascript">
      var canvas2Settings = {
        "target":"canvas2",
        "max":"500",
        "animate":true,
        "props":["circle","square","triangle","line",{"type": "svg", "src": "../site/face.png", "size": "100", "weight": .1}],
        "colors":[[165,104,246],[230,61,135],[0,199,228],[253,214,126]],
        "clock":"25",
		"rotate": true
      };
      var canvas2 = new ConfettiGenerator(canvas2Settings);
      canvas2.render();
      
    </script>
  </body>
</html>
