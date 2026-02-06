# ajaxify-cart

Snippet to ajaxify Your Shopify Cart.

(Use this only if your theme does not already use Ajax, of course.)

The following themes have been confirmed to work with the 'ajaxify-cart' solution without any configuration:

- Minimal
- New Standard

# How to install

Create a new snippet called **ajaxify-cart**. Paste in it the content of the ajaxify-cart.liquid file.

Then, include the ajaxify-cart snippet in your theme by pasting the code below in your <a href="http://www.shopify.com/admin/themes/current?key=layout/theme.liquid">theme.liquid</a> file right above your `</body>` tag:

`{% include 'ajaxify-cart' %}`

# How to configure (optional)

No configuration is necessary, but if you want or need to change a few things, go into your snippet and, at the bottom of it, change how the `Shopify.AjaxifyCart.init()` method is called, by passing to it a configuration object.
