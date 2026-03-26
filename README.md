# Softspring Flex Recipes

https://symfony.com/doc/current/setup/flex_private_recipes.html

## How to use private flex rpository

Update composer.json:

```json
{
    "extra": {
        "symfony": {
            "endpoint": [
                "https://api.github.com/repos/softspring/recipes/contents/index.json?ref=6.0",
                "flex://defaults"
            ]
        }
    }
}
```
