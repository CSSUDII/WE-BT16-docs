---
description: The Docs for the WE-BT16 API - Placeholders
---

# Placeholder API

{% api-method method="get" host="https://api.cssudii.tk" path="/v1/placeholders/:name" %}
{% api-method-summary %}
Placeholder API
{% endapi-method-summary %}

{% api-method-description %}
WE-BT16 Placeholder API
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="name" type="string" required=true %}
Name of the Placeholder to get
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Authentication token for the WE-BT16 API
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-query-parameters %}
{% api-method-parameter name="text" type="string" %}
Text to add to the response
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Placeholder successfully retrieved.
{% endapi-method-response-example-description %}

```
{    "name": "Example Placeholder",    "data": "Some Example Data",    "text": "Extra Text"}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Placeholder Not Found
{% endapi-method-response-example-description %}

```
{    "message": "404 Placeholder Not Found"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://api.cssudii.tk" path="/v1/placeholders/id/:id" %}
{% api-method-summary %}
Placeholder API by ID
{% endapi-method-summary %}

{% api-method-description %}
Get Placeholders by ID
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="id" type="string" required=true %}
ID of the placeholder
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Authentication token for the WE-BT16 API
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

