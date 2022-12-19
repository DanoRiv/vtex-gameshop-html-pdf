📢 Use this project, [contribute](https://github.com/{OrganizationName}/{AppName}) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# VTEX GAMESHOP HTML PDF

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

This app allows to add a PDF document and be rendered through an HTML PDF Reader.

![PDF Reader](https://res.cloudinary.com/dannt/image/upload/v1671167112/vtex-gs/danigameshop--itgloberspartnercl.myvtex.com_terminos-y-condiciones-de-servicio-tecnico_pjkouc.png)

## Configuration 

1. Add the PDF Reader app as a theme dependency in the `manifest.json` file:
```json
{
  "itgloberspartnercl.pdf-reader": "0.x"
}
```

2. Now, you are able to use all the blocks exported by the PDF Reader app. Check out the full list below:

| Block name   | Description  |
| :----------: | :------------------------: |
| `pdf-reader` | Renders a PDF reader to display a document on the page | 

Below you may find all available props to configure your pdf reader:

### `pdf-reader` props

| Prop name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | 
| `pdfUrl`      | `string`       | PDF Document's location         | `none`        |
| `width`      | `number`       | PDF Reader's rendering width         | `none`        |
| `height`      | `number`       | PDF Reader's rendering height         | `none`        |


## Customization

`No CSS Handles are available yet for the app customization.`

## Contributors 
1. Daniela Osorio Rivera
