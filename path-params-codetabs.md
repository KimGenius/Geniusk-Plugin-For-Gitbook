### path-params-codetabs example

I was inspired by the Google API.

##### codetabs
{% codetabs name="URI", type="bash" -%}
GET http://localhost/test?{param1}&{param2}&{param3}
{% language name="Sample", type="bash" %}curl http://localhost/test?param1={my}&param2={name}&param3={is}&param4={GeniusK}
{%- endcodetabs %}

##### path-params-codetabs
{% pathCodetabs name="URI", type="bash" -%}
GET http://localhost/test?{param1}&{param2}&{param3}
{%- language name="Sample", type="bash" -%}
curl http://localhost/test?param1={my}&param2={name}&param3={is}&param4={GeniusK}
{%- endpathCodetabs %}

[Code Link from Github](https://github.com/KimGenius/Geniusk-Plugin-For-Gitbook/blob/master/path-params-codetabs.md)