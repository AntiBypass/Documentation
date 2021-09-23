# Pop-up

{% api-method method="get" host="https://example.com" path="/api/popup.php" %}
{% api-method-summary %}
Get Pop-up Details
{% endapi-method-summary %}

{% api-method-description %}
The request is made directly to your AntiBypass Instalation
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
The response will be returned as a JSON file, which then can be read by briefly any software, please note that you might hide the pop-up if the `status` returns `false`.
{% endapi-method-response-example-description %}

```
{
    "status": true,
    "response": {
        "icon": "info",
        "title": "AntiBypass System",
        "message": "Example message"
    }
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



