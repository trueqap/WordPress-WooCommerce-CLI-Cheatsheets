# WooCommerce CLI Cheatsheets

### Delete all WooCommerce Products with WP-CLI

`wp post list --field=ID --post_type=product --posts_per_page=2000 | xargs wp post delete --force`

---

[Check the official WP-CLI documentation for additional information.](https://developer.wordpress.org/cli/commands/)
