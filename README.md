# Web app for Botanická zahrada Přírodovědecké fakulty Univerzity Karlovy

⚠️ Project is **no longer** in active development, but **still works**. ⚠️

> Note: This was created many years ago, as a fun volunteer project, in one hot summer by group of awesome and dedicated people

<p align="center" float="left">
  <a href="https://register.bz-uk.roamingowl.com/map"><img width="450" alt="image" src="https://github.com/roamingowl/bz-uk/assets/161971527/e14eb4f8-1b5d-43f2-85a6-1583f92e82cc"></a>
  <a href="https://register.bz-uk.roamingowl.com/map"><img width="143" alt="image" src="https://github.com/roamingowl/bz-uk/assets/161971527/e5951201-5ea6-45b5-823b-1dc11a83205f"></a>
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
 - searches over all the plants in botanical garde, and can show them on map
 - everything is cached offline (even map)


## Sources

Yea 😰... Those are mostly in private GitLab or private GitHub repos. It wouldn't be very safe & wise to publish them, nor they are relevant anymore.


