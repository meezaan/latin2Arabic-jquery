# A JQuery Plugin to convert Latin numbers to Arabic
This JQuery plugin basically takes all latin numbers in a string and converts them to the Arabic equivalent. It still needs some additional work and can also return the equivalent HTML symbol, or convert the other way around from Arabic to Latin numbers.

## How to use

Include the JS with:
```
<script src="/path/to/latin2Arabic.jquery.js"></script>
```

Then, in your code:
```
$(function() {
    var numbers = $.latin2Arabic.toArabic('15/2/1436');

    // numbers now contains: ١٥/٢/١٤٣٦
    // Now do whatever you wish to with numbers
    
    // You can also use the other methods
    var numbers = $.latin2Arabic.toLatin('١٥/٢/١٤٣٦'); // This will convert the latin to arabic
    var numbers = $.latin2Arabic.toHtml('١٥/٢/١٤٣٦'); // This will convert the arabic to html entities
});
```
