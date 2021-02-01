# Magento 2 Module to integrate fancybox

## Description

this module integrates the [fancybox jquery plugin](https://fancyapps.com/fancybox/3/).

## Install

Install the extension via composer:

```
composer install webidea24/magento2-module-fancybox
```

## Usage - Example

```
<script>
    require(['jquery', 'fancybox'], function($) {
        $().fancybox({"selector": "[data-fancybox='gallery']"});
    });
</script>
```

