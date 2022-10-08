# Alquiler-Cuatrimotos
# 🛵
***
En el siguiente repositorio se realizarala request por medio framework postman alacenandolos en la nube de oracle  tambien utilizaremos el lenguaje de java , se realizara una request para Guardar; Actualizar y Borrar informacion de un cliente.
Esta es una aplicacion MVC a Modelo Cliente Servidor

Tambien se creara un fronted para poder visualizar el formulario mediante Html y JavaScript

# IDE
# 🐱‍💻
***
[Netbeans](https://netbeans.apache.org/download/nb122/nb122.html)


# Oracle Cloud
# ☁☁☁
***
[Oracle Cloud](https://www.oracle.com/cloud/sign-in.html)

# Postman 
# 👩‍🚀
***
[Postman](https://www.postman.com/downloads/) 

# Servidor Web
# 👨‍💻
[Servidor Web](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb)

# Bibliotecas
***
JQeury
Para cargar una biblioteca alojada, copia y pega el fragmento HTML de esa biblioteca (que se muestra a continuación) en tu página web. Por ejemplo, para cargar jQuery, incorpora el fragmentoen tu página web. 
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script> 
```

Ajax
Ejemplo peticion AJAX con JQuery usado en el codigo 
```
$.ajax({    
	    url : myURLCliente,
	    type : 'GET',
	    dataType : 'json',
	    success : function(clients) {
	   		let cs=clients.items;
	   		$("#clients").empty();
	   		for(let i=0;i<cs.length;i++){
	   			let k=cs[i].id+" "+cs[i].name+" "+cs[i].email+" "+cs[i].age+" <button onclick='deleteClient("+cs[i].id+")'>borrar</button>";
	   			k+=" <button onclick='getDetailClient("+cs[i].id+")'>actualizar</button><br>"
	   			$("#clients").append(k);
	   		}
	    },
```

# Installation 
# ⚙
***
A little intro about the installation. 
```
git clone https://https.example.com
cd ../path/to/the/file
git checkout develop

this repository is this repository is hosted on the develop branch

```
