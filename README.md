# OS Components

A example map component and a geocoder component built with Polymer for Ordnance Survey APIs.

## Usage

Web components allow you to quickly add reusable elements to your page just like native HTML elements (div, span, p etc). Here we can quickly add a OS Map to our page using the following HTML (dependency imports assumed in the head):

    <body>
        <os-map basemap="road" crs="wgs84" zoom="7"><os-map>
    </body>

See the Demo subheading below for more information on seeing a live demo.

## Dependencies Used

* Leaflet - Underpinning mapping framework
* Polymer - Web Components library
* Geodesy - Library for transforming coordinates between WGS84 and BNG and vice versa
* webcomponents.js - Web components polyfill for non compliant browsers

## Screenshot

![Screenshot OS Components](https://raw.githubusercontent.com/Geovation/os-components/master/os-components-screenshot.png)

## Install

    bower install

## Demo

Get your Ordnance Survey API key, and create a file called apikey.js which resides in the os-components folder. In the file place:

    var osApiKey = "YOUR_API_KEY_HERE12345"; // Change with your API Key

Then you can use :

    npm install -g live-server
    live-server

From the folder to serve the demo. Alternatively copy the files to your web server of choice.
