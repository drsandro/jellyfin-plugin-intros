<h1 align="center">Jellyfin CUSTOM Intros Plugin</h1>
<h3 align="center">Part of the <a href="https://jellyfin.org">Jellyfin Project</a></h3>

<p align="center">
This is a plugin built with DotNet that can download flashy intros from vimeo.com for your movies. With this fork, you can use your custom videos from vimeo.com. Just set the vimeo-Video-ID (i.e. https://vimeo.com/<b>443404335</b>) in the settings of this plugin.
</p>

## Build Process

1. Clone or download this repository

2. Ensure you have DotNet Core SDK setup and installed

3. Build plugin with following command

```sh
dotnet publish --configuration Release --output bin
```

4. Place the resulting file in the `plugins` folder
