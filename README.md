Debemos tener instalado mongo comunity server, ademas de crear un movil desde  Device Manager en android studio
En el cual expo nos instalara lo necesario para la aplicacion


En el proyecto debemos cambiar en el archivo
authContext.js

en la linea 30
  axios.defaults.baseURL = "http://192.168.246.36:8080/api/v1";
reemplazamos por nuestra ip actual

Para iniciar el proyecto debemos abrir dos terminales

La primer terminal desde cd client
La segunda terminal desde cd server

En la primer terminal debemos ejecutar 
npm run start

En la segunda terminal debemos ejecutar
npm run server

