E-commerce

1. Create Folder structure
   1. create root folder as E-commerce
   2. add frontend and backend folder
   3. create src folder in frontend 
   4. create.index.html with heading E-commerce in src
   5. run npm init in frontend folder
   6. npm install live-server
   7. add start command as live-server src --verbose
   8. run npm start

2. DEsing Website
   1. create stryle.css
   2. link style.css to index.html
   3. creat div.grid-container
   4. create header, main and footer
   6.style grid-container, header, main and footer  

3. Create static home screen
   1. create ul.products
   2. create li
   3. create div.product
   4. add.product-image, .product-name, .product-brand, .product-price
   5. style ul.products and internal divs
   6. duplicate 2 times to show 3 products

4. Render Dynamics home screen
   1. create date,js
   2. export an array of 6 products
   3. create screen/homeScreen.js
   4. export HomeScreen as an objet with render() method
   5. implement render()
   6. import data.js
   7. return products mapped to list inside an ul
   8. create app.js
   9. link it to index.html as module
   10. set main id to main_container
   11. create router() function 
   12. ser main_container innerHTML to HomeScreen.render()
   13. set load event of window to router() function

5. Build Url Router
   1. create routes as route/;screen objet for home screen
   2. create utils.js
   3. export parseRequestURL()
   4. set url as hash address split by slash
   5. return resource, id and verb of url
   6. update router()
   7. set request as parseRequestURL()
   8. build parseUrl and compare with roites
   9. if route exists render it, else render Error404
   10. create screen/Error404.js and render error message


