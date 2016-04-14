# Práctica 2: Comma separated values (CSV) with AJAX

## INFO:

### jQuery.get( url [, data ] [, success ] [, dataType ] )
* url
  * Type: String
  * A string containing the URL to which the request is sent.
* data
  * Type: PlainObject or String
  * A plain object or string that is sent to the server with the request.
* success
  * Type: Function( PlainObject data, String textStatus, jqXHR jqXHR )
  * A callback function that is executed if the request succeeds. 
    Required if `dataType` is provided, but you can use `null` or `jQuery.noop` as a placeholder.
* dataType
  * Type: String
  * The type of data expected from the server. Default: Intelligent Guess (xml, json, script, text, html).

### jQuery.get( [settings ] )
* settings
  * Type: PlainObject
  * A set of key/value pairs that configure the Ajax request. 
  * All properties except for `url` are optional. 
  * A default can be set for any option with `$.ajaxSetup()`.

This is a shorthand Ajax function, which is equivalent to:

```javascript
$.ajax({
  url: url,
  data: data,
  success: success,
  dataType: dataType
});
```

The success callback function is passed the returned data, which will be an XML root element, text string, JavaScript file, or JSON object, depending on the MIME type of the response. It is also passed the text status of the response.

## HEROKU 
https://cvsajax.herokuapp.com/

## DEVELOPERS

### Adrián Rodríguez Bazaga
  - Email: arodriba@ull.edu.es
  - [Página personal](http://adrianbzg.github.io)

### Rudolf Cicko
  - Email: alu0100824780@ull.edu.es
  - [Página personal](http://alu0100824780.github.io)

**Enlace al campus de la asignatura Procesadores de Lenguajes:**

* [Procesadores de Lenguajes](https://campusvirtual.ull.es/1516/course/view.php?id=178)


### Validación por www.W3.org (validator.w3.org)
Resultado: 0 errores y 0 warnings.
![W3 Validation](http://i.imgur.com/hqHRNup.png?1 "W3 Validation")

### Métricas JSHint (http://jshint.com/)
Resultado: 0 errores y 0 warnings.
![JSHint Metricas](http://i.imgur.com/4zDVjyW.png?1 "JSHint Metricas")

