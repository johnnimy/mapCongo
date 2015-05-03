# mapCongo
<html>
<head>

<title>BIENVENUE DANS LE MAP DE LA PROVINCE DU NORD KIVU</title>
<script src="http://maps.google.com/maps/api/js?sensor=false"></script>
<script>
function john(){
var divma=document.getElementByIdt("monmap");
var mapOption={
			center: new google.maps.LatLng(28.75,-0.66667),
			zoom:15,
			mapTypeId: google.maps.MapTypeId.SATELLITE
};
var map=new  google.maps.Map(divma,mapOption);
}
window.onload=john;

</script>
<style type="text/css">
#monmap{
width:100px;
height:700px;
}
body
{
font-family:verdana;
font-size:12px;
font-style:italic;
background-image:src="

}
#papa
{
width:800px;
margin:auto;
}

#haut
{
padding:10px;
height:100px;
padding:10px;
}
#liens{
padding-top:10px;
height:30px;
}
#milieu
{
height:400px;
background:#eee;
}
#bas
{
height:20px;
background:#999;
}
#liens a{
margin-right:12px;
display-block:none;
background:#DDD;
padding:10px;
text-decoration:none;
}
#liens a:hover{

background:orange;
}

</style>

<head>
<body>
<div id ="papa">
		<div id ="haut">
		<img src="HTML/TRA.PNG" width="200" height="96" alt="logo"/>
		
		</div>
		
		<div id ="liens">
		<a href="http\\www.google.com">ACCUEIL</a>
		<a href="http\\www.google.com">ACTUALITE</a>
		<a href="http\\www.google.com">VISITE LA VILLE</a>
		<a href="http\\www.google.com">FORET</a>
		
		</div>
		<div id="milieu">
		<h2>LE MAP DU NORD KIVU</h2>
		
		<div id ="monmap">
		
		
		</div>
		
		</div>
		le milieu
		</div>
		<div id="bas">
		le bas de la 
		</div>

</div>

 
</body>

</html>
