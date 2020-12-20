Simple Client-Server application.
Servlet deployed in the Tomcat.
The JAR contains all the necessary dependencies, including the Phone Object from the local repository.
I entered in the browser the following request with parameters:
http://localhost:8080/ServletApp/hello?brand=Samsung&color=Turquoise&diagonale=7.4&weight=200
The servlet returned a JSON in the browser:
{"brand":"Samsung","color":"Turquoise","diagonale":7.4,"weight":200}
