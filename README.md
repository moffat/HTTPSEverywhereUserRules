HTTPSEverywhereUserRules
========================

Algunas reglas para usar con el plugin para Firefox HTTPSEverywhere, particularmente para sitios en Chile que tienen sitios servidos por TLS (i.e. https) pero no lo hacen por defecto.

Notas:

* No he probado estas reglas con el plugin para Chrome o Opera. 
* Si tienes problemas con las reglas, la solución más fácil es borrarla y reiniciar Firefox.

Modo de uso:

1.- Instalar HTTPSEverywhere en Firefox: https://www.eff.org/https-everywhere

2.- Bajar la o las reglas que te interesan usar (baja el archivo .zip si no usas GitHub)

3.- Instalar el archivo en el directorio HTTPSEverywhereUserRules/ que está bajo el directorio del perfil de firefox. Por defecto, este directorio está [ubicado en](http://kb.mozillazine.org/Profile_folder_-_Firefox#Navigating_to_the_profile_folder "Profile folder - Firefox - MozillaZine Knowledge Base") está en:

* Linux: ~/.mozilla/firefox/<profile folder> 
* OS X: 
    * ~/Library/Application Support/Firefox/Profiles/<profile folder>
    * ~/Library/Mozilla/Firefox/Profiles/<profile folder> 
* Windows: %APPDATA%\Mozilla\Firefox\Profiles\<profile folder> 

4.- Reiniciar Firefox. Cuando visites el sitio en cuestión, deberías ver https:// en la barra de navegación, y la regla debería aparecer en el ícono de HTTPSEverywhere

