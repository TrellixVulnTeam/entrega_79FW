//COMO EMPEZAR A COMPILAR SASS//

1. Abrir la consola en esta carpeta con ctrl+ñ. 
npm install nodemon node-sass. 
npm init

2. Abrir el archivo package.json y editarlo. A continuación de && exit 1" colocar una , presionar enter y pegar el siguiente texto:

"build-css": "node-sass --include-path scss scss/main.scss css/style.css",

"watch-css": "nodemon -e scss -x \"npm run build-css\""

3. Crear las carpetas con sus respectivos archivosa. scss/main.scssb. css/style.css

4. En la consola correr el comandoa. 
npm run build-css // Por unica vez. 
npm run watch-css

5. Cada vez que se quiera seguir compilando en SASS. abrir la consola con ctrl+ñ. 
npm run watch-css

//FIN

