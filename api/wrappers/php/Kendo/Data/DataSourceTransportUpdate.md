---
title: DataSourceTransportUpdate
slug: php-DataSourceTransportUpdate
tags: api, php
publish: true
---

# \Kendo\Data\DataSourceTransportUpdate

A PHP class representing the update setting of DataSourceTransport.


## Methods

### cache `boolean`

If set to false, it will force requested pages not to be cached by the browser. Setting cache to false also appends a query string parameter, "_=[TIMESTAMP]", to the URL.
Refer to the jQuery.ajax documentation for further info.


#### Example - using boolean
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->cache(true);

### contentType `string`

The content-type HTTP header sent to the server. Default is "application/x-www-form-urlencoded". Use "application/json" if the content is JSON.
Refer to the jQuery.ajax documentation for further info.


#### Example - using string
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->contentType('value');

### data `|string|\Kendo\JavaScriptFunction`

Data to be send to the server.
Refer to the jQuery.ajax documentation for further info.


#### Example - using 
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->data(new ());

#### Example - using string
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->data('value');

#### Example - using \Kendo\JavaScriptFunction
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->data(new \Kendo\JavaScriptFunction('function() { }'));

### dataType `string`

The type of data that you're expecting back from the server. Commonly used values are "json" and "jsonp".
Refer to the jQuery.ajax documentation for further info.


#### Example - using string
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->dataType('value');

### type `string`

The type of request to make ("POST", "GET", "PUT" or "DELETE"), default is "GET".
Refer to the jQuery.ajax documentation for further info.


#### Example - using string
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->type('value');

### url `string|\Kendo\JavaScriptFunction`

The remote url to call when creating a new record.


#### Example - using string
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->url('value');

#### Example - using \Kendo\JavaScriptFunction
    $update = new \Kendo\Data\DataSourceTransportUpdate();
    $update->url(new \Kendo\JavaScriptFunction('function() { }'));
