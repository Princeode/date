
<html>
<head>
<title>prince</title>

<script type="text/javascript">
flag=1
function f1()
{
    var Name = prompt("what should I call you?");
    
    if(Name == "" || Name == null) {
    alert("please enter your name.");
    } else {
    alert("Hi " + Name + ", Naneto pakipot pa payag din namn."); 
    }
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1> Hi crush date tayo mamaya?</h1>
<img src="https://media.tenor.com/ufd0ItHQVaIAAAAC/mochi-mochimochi.gif" height="200" />
<h1 style="#">Payag ka or Hindi?</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" Sige " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" Ayaw " onMouseOver="f()" />
</div>

</body>
</html>
