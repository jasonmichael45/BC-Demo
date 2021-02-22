# BC-Demo

Preview code: mpmh5038yp

[x]Create a product called Special Item which will be assigned to a new category called Special Items. Be sure to add at least 2 images during the product creation

[x]The Special Item should be the only item which shows in this category 

# Unfinished; pseudocode solutions

* []create a feature that will show the product's second image when it is hovered on.

 product-view.html: set data-zoom-image to 2nd image

* []Add a button at the top of the category page labeled Add All To Cart. When clicked, the product will be added to the cart. Notify the user that the product has been added.

 navigation.html: <li> Add To Cart {{components/products/add-to-cart}} </li>


* []If the cart has an item in it - show a button next to the Add All To Cart button which says Remove All Items. When clicked it should clear the cart and notify the user.

 {{if cart size > 0}} <li> Remove All Items </li> {{/if}}


* []Both buttons should utilize the Storefront API for completion.

Bonus

* []If a customer is logged in - at the top of the category page show a banner that shows some customer details (i.e. name, email, phone ,etc). This should utilize the data that is rendered via Handlebars on the Customer Object.
