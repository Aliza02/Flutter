Previous Code
Void main=>runApp(MaterialApp(
Home:Text(‘hello world”),
))
Scaffold And Appbar
Scaffold is a widget that allow implementation of basic layout. e.g: setting up appbar, button 
*All widgets are already built in flutter SDk we can have customize widgets as well.
Now the above code can be written as 
Void main=>runApp(MaterialApp(
home:Scaffold(
//Scaffold will define basic layout of app
//To define application bar we have property names as appBar
// every property in flutter takes widget as value
appBar:AppBar(
title:Text(‘My App’),
centerTitle:true,
),
body:Center(

//center widget centralize everything  inside this.
child:Text(‘Hello world’),
),
floatingActionButton:floatingActionButton(
child:Text(‘click’),
),
),

))
