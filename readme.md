# WooCommerce display top customers
> WooCommerce display top customers is a plugin that allows just that.

Adds the shortcode [wc_top_customers] to WooCommerce and shows a list of customers ordered by the number of their completed orders.

# Usage

`[wc_top_customers number="12" columns="4" orderby="meta_key" orderby_meta_key="_order_count" order="asc" role="customer"]`

# Shortcode Parameters

* **number**: The maximum number of customers to show. Default *12*
* **columns**: The number of columns to use for the grid. Default *4*
* **orderby**: The order key used to show customers. Default *meta_key*
* **orderby_meta_key**: Order customers by orders count (_order_count) or money spent(_money_spent). Default *_order_count*
* **order**: Shows customer in ascending or descending order. Default *asc*
* **role**: Show customers with the role assigned to this attribute. Default *customer*