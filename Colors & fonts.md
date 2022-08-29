	Void main=>runApp(MaterialApp(
	home:Scaffold(
	//Scaffold will define basic layout of app
	//To define application bar we have property names as appBar
	// every property in flutter takes widget as value
	appBar:AppBar(
	title:Text(‘My App’),
backgroundColor:Colors.rede[600],
	centerTitle:true,
	),
	body:Center(
	

	//center widget centralize everything  inside this.
	child:Text(‘Hello world’
style:TextStyle(
fontSize:10.0,
fontWeight:FontWeight.bold,
letterSpacing:3.0,
color:Colors.grey[600],
/// in order to use custom font family
//get the font from google fonts and add it in project
//make a folder in root directory and place the font in it
// now in order to use the font go to pubspec.yaml
//add font in font property
fontFamily:’Lato’,
),
),
	),
	floatingActionButton:floatingActionButton(
onPressed: (){},
	child:Text(‘click’),
backgroundColor:Colors.red[600],
	),
	),
	

	));

