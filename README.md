javascript
==========

javascript


:
<input/>
<input name="ninin"  value="firstname">
 
<input name="ninin" value="dd"/>
 
 <lable> <input type= name="firstname"/> </lable><br>
<input type="password" name="lastname">
<input type="checkbox" name="lastname">
<input type="hidden">
<input type="image"  src="C:\gg.jpg" alt="hi"/>
<button>jjf  ff</button>
<select name="nijn"><option value="s">qq</option>
<option value="s">dq</option>
<option value="s">eww</option>
<option value="s">dd</option>




<input type="date">


web form and death  <--- cource
css:style form  <--- cource
<input type="color">

website--->can i use website

 maxlength="3" min="2"
<input name="name" maxlength="2" required placeholder="pls enter your name" id="namefield" />


<input type="email" multiple name="email" id="emailfield" /> //send multiple mail
website<-- html 5 pattern
website-->mime media type


 
regexpal <--- online tool
requler express cheet sheet <--search google
using reguler expresstion <--- cource


33.google crome right click  inspct elements - console type
document.getElementById("myform")
document.getElementById("myform").getElementByTagName("input")[1]
document.getElementById("myname")
document.theform.myname.ty
undefined
document.theform.myname.type
"text"
document.theform.myname.id
"myname"
document.theform.myname.value
""
document.theform.myname.ATTRIBUTE_NODE
2
document.theform.myname.type="radio"
"radio"
document.theform.myname.type="text"
"text"


34... handle form -->> onfocus,onblur



document.theform.myname.onfocus=function() {
 	document.getElementById('mynamehint').innerHTML = "(Enter last name as nijan, then first)";
	}

	document.theform.myname.onblur=function() {
		document.getElementById('mynamehint').innerHTML = "";
	}

url for validation:
<script>

	document.theform.myurl.onblur=function() {
		if (document.theform.myurl.value==="") {
			document.getElementById("formerror").innerHTML = "The URL field is required";
		} //url empty

		if (document.theform.myurl.value==="http://") {
			document.getElementById("formerror").innerHTML = "Pleae add a valid URL";
		} //url empty


	} //onblur



	document.theform.myurl.onchange=function() {
		var theURL = document.theform.myurl.value;

		if (theURL.indexOf("http://")) {
			document.getElementById('formerror').innerHTML = "URLs must begin with http://";

			document.theform.myurl.value = "http://"+document.theform.myurl.value;
		} // doesn't have http://

	} //onchange
</script

