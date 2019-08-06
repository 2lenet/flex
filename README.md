## Flex Symfony

```
 composer config extra.symfony.id
```

Add the id in config.json : https://github.com/2lenet/flex/blob/master/config.json

For to have an id add this in composer.json of your project:
```
"extra": {
        "symfony": {
            "id": "...MY ULID...",
            "allow-contrib": true,
        }
    }
```

It's OK --> http://fabien.potencier.org/symfony4-flex-private-repositories.html

But do not work since a moment

## Flex Aurimasniekis (flex.2le.net)

https://github.com/aurimasniekis/flex-server

add endpoint in your project composer.json

```
"extra": {
        "symfony": {
            "endpoint": "https://flex.2le.net"
        }
    }
```

It's work (compose require attachment)



---------------------------------------------

# Update your recipes

Just change this repository the first methode is OK

For the flex.2le.net run update.sh on Japet after change this repo
