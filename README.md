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
    var numbers = $.latin2Arabic.toArabic('15/02/1436');

    // numbers now contains: ١٥/٢/١٤٣٦
    // Now do whatever you wish to with numbers
});
```
