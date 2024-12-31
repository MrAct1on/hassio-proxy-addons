<div align="center">
    <a href="https://github.com/MrAct1on/Hassio-Proxy-Addons">
        <img width="150" height="150" src="Hassio-Proxy-Addons/logo.png">
    <h1>Action's Officisl Proxy Home Assistant addon</h1>
</div>

This addon acts as a proxy to an external running URL instance. 
The sole purpose of this addon is to add an icon to the sidebar of Home Assistant which will open the frontend of an external running URL instance.

## Options

- `server` (required): Set the local URL on which the page is running, e.g. `http://192.168.2.43:8080`. Make sure there is no trailing slash!
- `auth_token` (optional): only use when you have an `auth_token` set for the frontend in the URL configuration.
