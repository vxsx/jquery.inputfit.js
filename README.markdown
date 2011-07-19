#jquery.inputfit.js
Plugin that makes value of the input fit into the input, see the [demo](http://vxsx.github.com/jquery.inputfit.js/)
  
Requires  

*  jquery 1.4.4 or higher

Default options 

``` javascript
minSize : 12
maxSize : 24
```

Using:

``` html
<input type="text" name="younameit" id="input">
<script type="text/javascript">
    $('input').inputfit();
</script>
```
Plugin fits text by changing the font-size, so you should set min and
max font-size values. Oh, and it relies on id of the element. It doesn't
have to be called by id, but it should have it anyway.


Note
-------
I just needed this functionality for our company's project, it works
alright with some potential tweaking in *all* browsers (IE6+, CHR, SAF,
FF3+, O10+ etc.). Please, file an issue if something is broken, I
promise I'll look in to it)



TODO:
-----

* refactor "id" dependency
* fix jumps in some cases
* fix all hardcode :(
