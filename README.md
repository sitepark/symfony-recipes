# Symfony Flex Recipes

This repository is hosting Symfony Flex Recipes for Sitepark

You can look into the [Symfony documentation](https://github.com/symfony/recipes#creating-recipes) for more information about the recipe format.

See also [Create an Index to the Recipes](https://symfony.com/doc/current/setup/flex_private_recipes.html#create-an-index-to-the-recipes) to add more recipes

Please add the following entry to your `composer.json` to use the recipes.

```json
"extra": {
    "symfony": {
	"allow-contrib": true,
        "endpoint": [
           "https://api.github.com/repos/sitepark/symfony-recipes/contents/index.json?ref=flex/main",
           "flex://defaults"
        ]
    }
}
```
