Ejercicio 2

$.get("https://randomuser.me/api/?results=1000", function(data){											var a=data.results;														
Ejercicio 3

$.get("https://randomuser.me/api/?results=1000", function(data){											var a=data.results;														a.map((x) =>console.log(x.name.first+" "+x.name.last));										})})


