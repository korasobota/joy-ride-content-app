# joy-ride-content-app

This repository is used for applying a generic approach of Joyride component for app startpages. The repo contains .json files for the apps or modules we need to add the joy ride funcationality inside.

The the name of the json file should fellow the following naming schema: joy-ride-{App_Name}.json.

Inside the file, we are initialising the following properties for every joy ride step:

id: accepts the number of the step.
title: the English title of the step.
title_de: the German title of the step.
content: the English content of the step.
content_de: the German content of the step.
target: the target HTML element that the step should display on the page,
placement: the position of the joy ride step on the page.


The sample layout of the Json file should be like the following : 

```json
[
{
"id": 1,
"title": {
"en": "Start",
"de": "Anfang"
},
"content": {
"en": "Let's begin our journey!",
"de": "Los geht's!"
},
"target": ".container-fluid",
"placement": "center"
},
{
"id": 2,
"title": {
"en": "Step 1",
"de": "Shritt 1"
},
"content": {
"en": "This is step 1",
"de": "Das ist Schritt 1"
},
"target": ".container-fluid",
"placement": "top-end"
},
{
"id": 3,
"title": {
"en": "Step 2",
"de": "Shritt 2"
},
"content": {
"en": "This is step 2",
"de": "Das ist Schritt 2"
},
"target": ".container-fluid",
"placement": "top-end"
}
]
```
**N.B: If the new language is not specified for title or content attributes, the default English values will be displayed**
