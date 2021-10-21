# WebPack

En este repositorio se guardara la configuracion inicial de webpack

Antes de hacer un git clone es necesario que en una carpeta nueva ejecutes:
```
npm init
```
Despues es necesario instalar alguna dependencias de desarrollo para que no tenga errores
```
npm install -D webpack webpack-cli babel-loader @babel/core @babel/preset-env html-webpack-plugin html-loader mini-css-extract-plugin css-loader 
```
Y por ultimo instalar react
```
npm install --save react react-dom
```
Despues de esto ejecutamos:
```
git init
```
Y en lugar de crear un clon del repositorio vamos a hacer un pull
```
git remote add origin https://github.com/diegoufp/WebPack.git
```
```
git pull origin master --allow-unrelated-histories
```

## npm run
Se tienen 3 comandos en la configuracion inicial de web pack:
- `npm run dev`: hambiente de desarrollo
- `npm run buil`: hambiente de produccion
- `npm start`: se inicial un servidor en el puerto 5000 y se abre automaticamente el navegador
