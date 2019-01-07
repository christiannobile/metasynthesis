# JQuery
## 1 : Immidiate Actions
1. Adress element by ID Change property display to none
```
$("#ID").hide();
```
2. Adress element by ID Change property display to block
```
$("#ID").show();
```
3. Adress element by ID Change property font-family to Courier
```
$("#ID").css('font-family','Courier');
```
4. Adress element by TAG Change property color to red
```
$("TAG").css('color', 'red');
```
5. Adress element by ID Change InnerHTML to empty
```
$("#ID").empty();
```
6. Adress element by CLASS Change property display to none
```
$(".CLASS").hide();
```
7. Adress element by CLASS Change removeHTML
```
$('.CLASS').remove();
```
8. Adress element by TAG in TAG Change property color to red
```
$('TAG TAG').css('color', 'red');
```
9. Adress element by ID's Change property border to 5px dotted green
```
$('#ID, #ID').css('border', '5px dotted green');
```
10. Adress element by ID add CLASS adressed in 6 / Hide subject CLASS
```
$('#ID').attr('class', '.CLASS');
$(".CLASS").hide();
```

## SUMMARY
Adress element by #ID TAG .CLASS
```
$('ELEMENT').
```
Adress Multiple Elements
```
$('ELEMENT , ELEMENT').
```
Adress Nested Element
```
$('ELEMENT ELEMENT').
```
**Perform Action**
Change Visibility
```
hide();
show();
```
Change Property
```
css('Property','Value');
```
Change Attribute
```
attr('ATTRIBUTE', 'VALUE');
```
Remove InnerHTML 
```
empty();
```
Remove HTML
```
remove();
```
