# Web app for Botanická zahrada Přírodovědecké fakulty Univerzity Karlovy

⚠️ Project is **no longer** in active development, but **still works**. ⚠️

> Note: This was created many years ago, as a fun volunteer project, in one hot summer by group of awesome and dedicated people

<p align="center" float="left">
  <img width="450" alt="image" src="https://github.com/roamingowl/bz-uk/assets/161971527/e14eb4f8-1b5d-43f2-85a6-1583f92e82cc">
  <img width="143" alt="image" src="https://github.com/roamingowl/bz-uk/assets/161971527/e5951201-5ea6-45b5-823b-1dc11a83205f">
</p>
<p align=center>
  See it <a href="https://register.bz-uk.roamingowl.com/map">live</a>
</p>

## Tech stack

This was many years ago, but it all **still works** together 🙂  
Anyways, these are tha main parts:
- php
- angular 1
- react 15
- leaflet
- pwa
- webpack 2.x
- nodejs
- ...and many more libs


# Application parts

App consists of 3 parts: 
- map and registry ([see it live](https://register.bz-uk.roamingowl.com/map))
  - angular frontend
  - php backend  
- administration
  - angular & react frontend
  - php & nodejs backend
- main web-page extension ([see it live](https://bz-uk.cz/))
  - react injected into drupal pages

 ## Map and registry

 So this is the **main part** of the whole project. Consist of single page application (made in angular) on frontend, backed by PHP backend on [lumen](https://lumen.laravel.com/docs/11.x).

 Main features:
 - responsive
 - SPA (sinlge page app)
 - pwa (can be installed on mobile)
 - based on materialUI (kind of)
 - has map (png tiles, rendered from huge svg)
 - has extensive botanical content
 - has QR scanner directly in JS
 - live GPS location
 - searches over all the plants in botanical garde, and can show them on map
 - everything is cached offline (even map)

## Some examples

https://github.com/roamingowl/bz-uk/assets/161971527/ef41ebca-a9f0-43bf-914f-a18fe3e2e457
<p align=center>
  Mobile view - example of expositon info
</p>



https://github.com/roamingowl/bz-uk/assets/161971527/ba287a9c-23c3-49d7-9bb9-817e5716be31
<p align=center>
  Tablet view - plant detail
</p>




https://github.com/roamingowl/bz-uk/assets/161971527/605ee416-27f7-472a-b03d-2d4f0a9af839
<p align=center>
  Tablet view - searching plants
</p>





## Sources

Yea 😰... Those are mostly in private GitLab or private GitHub repos. It wouldn't be very safe & wise to publish them, nor they are relevant anymore.


