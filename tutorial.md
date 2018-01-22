# selector
este selector llama a un conponente 
<app-componente></app-componente>

template
app.componente.html
styles
app.componente.css


import 
importa otros componentes desde angular core

export
permite que se utilice la clase en otros componentes

pone en servicio la app y la habre en el navegador
ng serve -o

crear un nuevo componente
ng g c componentenuevo
esto indica que no debe tener css y sin estar dentro de una carpeta
is flat


app.module.ts es el modulo root si se crea con el cli se agrega automaticamente
los componente deben tener un componente main

tutorial galeria de imagenes 5 de jesus conde
integrar assets todos loe elementos a crear

barra de navegacion, tutorial 6
ng g c navbar -is --flat
no tendra un css y se creara dentro de la carpeta app

ng g c gallery