# Apex Bootstrap Theme

A custom [Bootstrap](http://getbootstrap.com/) theme for Apex Clearing.

This repo contains the contents of the .zip file from the [Bootstrap Customizer](http://getbootstrap.com/customize/?id=b589cfa181359d6cae577764d6784a4f). The Customizer saves a version of this theme that can be accessed and modified [here](http://getbootstrap.com/customize/?id=b589cfa181359d6cae577764d6784a4f). Alternatively, you can upload the `config.json` file to the customizer.

## Usage

The [React Boilerplate](https://www.reactboilerplate.com) WebPack configuration allows CSS files from the `node_modules/` directory to be imported directly into `app.js`:

  `import 'apex-bootstrap-theme/css/bootstrap.css';`

For ease of maintenance this repo contains the whole contents of the custom Bootstrap theme, but you probably only need `bootstrap.css`. `bootstrap.theme.css` contains gradient styles and animations that we don't currently use, and font-awesome is a more robust drop-in replacement for the glyphicon-halflings fonts in the `fonts/` directory.
