# JavaScript-Function-To-Perform-Mathematical-Operations
<html>
<head>
<title>math</title>
   <script type= "text/javascript ">
  <!--
	function oper()
	{
		var ch=parseInt(prompt( "Enter your choice 1.Addition 2.Subtraction 3.Multiplication 4.Division "));
            	switch(ch)
	{
		case 1:var v1=parseInt(prompt( "Enter the first value "));
		           var v2=parseInt(prompt( "Enter the second value "));
		           var v3=v1+v2;
		           document.writeln( "<br> "+ "Addition: "+v3);
		           break;
		case 2:var v4=parseInt(prompt( "Enter the first value "));
		           var v5=parseInt(prompt( "Enter the second value "));
		           var v6=v4-v5;
		           document.writeln( "<br> "+ "Subtraction: "+v6);
		           break;
		case 3:var v7=parseInt(prompt( "Enter the first value "));
		           var v8=parseInt(prompt( "Enter the second value "));
		           var v9=v7*v8;
		           document.writeln( "<br> "+ "Multiplication:  "+v9);
		           break;
		case 4:var v10=parseInt(prompt( "Enter the first value "));
		           var v11=parseInt(prompt( "Enter the second value "));
		           var v12=v10/v11;
		           document.writeln( "<br> "+ "Divison: "+v12);
		           break;
		case 5:var v13=parseInt(prompt( "Enter the first value "));
		           var v14=parseInt(prompt( "Enter the second value "));
		           var v15=v13%v14;
		           document.writeln( "<br> "+ "Modulus: "+v15);
		           break;
		default: document.writeln( "Enter choice correctly ");
	}

}
</script>
</head>
<body onLoad= "oper()"></body>
</html>
