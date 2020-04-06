# shipperportal-template

Create as many template you want in any format.
Template can be json, text or html...

# Step to create a new template :

1. create a folder with your template Name ex : carrier_rubiwin_82
2. create file with and name it with local and what ever format you want ex: `fr.json` `fr.html` `fr.xml`

# How to retrieve my template ? 

Post to : https://shipperportal.test.flash.global/api/template/:template_name/:template_lang/:template_format

if you have customized your template with mustash {{parameter}}, just post your parameter :

```json
{
    "parameter": "value"
}
```
