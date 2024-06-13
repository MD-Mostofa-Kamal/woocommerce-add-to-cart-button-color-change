# woocommerce-add-to-cart-button-color-change

To change the color of the "Add to Cart" button in WooCommerce, you'll need to add some custom CSS to your theme. Specifically, you'll be targeting the .single_add_to_cart_button class. Here's how you can do it:

# Sometimes, plugins and themes can conflict with your CSS. To avoid this, ensure your CSS classes or IDs are correctly specified, and then paste the following code.


# Steps to Change the "Add to Cart" Button Color
Log in to your WordPress Dashboard:

Go to Appearance > Customize:

Navigate to Additional CSS:

Add the following CSS code:
```html
.single_add_to_cart_button {
    background-color: #ff0000; /* Change this to the desired background color */
    color: #ffffff; /* Change this to the desired text color */
}

.single_add_to_cart_button:hover {
    background-color: #cc0000; /* Change this to the desired background color on hover */
    color: #ffffff; /* Change this to the desired text color on hover */
}  
```

# Steps to Change the "Add to Cart" Button Color on Archive Pages
```html
.add_to_cart_button {
    background-color: #ff0000; /* Change this to the desired background color */
    color: #ffffff; /* Change this to the desired text color */
}

.add_to_cart_button:hover {
    background-color: #cc0000; /* Change this to the desired background color on hover */
    color: #ffffff; /* Change this to the desired text color on hover */
}

```


