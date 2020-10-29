# react_router
/**
 * 1 X Instalar react-router-dom
 * 2 X Incluir Navbar En App.js
 * 3 X Colocar Router
 * 4 X Convertir las Rutas del NavBar.js en NavLink
 * 5 X Basandose en las rutas del Navbar, crear un switch en APP.js que enrute cada ruta con su componente
 * 6 X En cada componente, implementar metodo Constructor con SUPER y un estado. Por ejemplo: 
 *    En el constructor de Posts, colocar un estado como: this.state = {posts:[]};
 * 7En cada componente, implementar componendDidMount.
 * 8En cada componente, consumir en el lugar correcto un fetch al servicio de jsonplaceholder correspondiente. 
 *    Por ejemplo, en Posts: 
 *    fetch('https://jsonplaceholder.typicode.com/posts')
 * 9- Guardar la respuesta de los servicios en el estado de cada componente.
 * 10- Renderizar correctamente en cada componente los resultados guardados en el estado.
 *    Se puede utilizar: <ul> <ol> <table> o componentes de Bootstrap (Cards, etc.)
 * 
 * ****Extras***
 * 
 * 11- Acomodar el proyecto para que La estructura de carpetas sea como veniamos trabajando
 * 12- Crear un componente llamado "ShowData" que reciba el dato y el formato y decida si renderizar un LI / TR / CARD
 * 13- Guardar en localStorage el dato traido del servicio. Luego, antes de consumir el servicio, consultar si existe el dato en el LOCALSTORAGE. Si existe, no hacer nuevamente el fetch!
 * 
 */
