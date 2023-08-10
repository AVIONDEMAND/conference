# Conference

AVI conference is a theme for conferences/events based on the original [conf-boilerplate theme](https://github.com/braziljs/conf-boilerplate/) by [BrazilJS Foundation](http://braziljs.org/) and his many contributors.

## Building

1. Install [Hugo](https://gohugo.io)
2. Create a new site by running:

```shell
        git clone https://github.com/AVIONDEMAND/conference my-conf
        cd my-conf
        rm -f config.toml
        cp themes/avicon/exampleSite/config.toml .
```

3. It's done. Just start Hugo server to see it live!

```shell
        hugo server --watch
```

## Customizing

All the site information can be found in the `config.toml` file. Just edit it to make changes. By default, the site have the following sections:

* About    - to describe what's the main goal of your event.
* Blog     - to follow upcoming news and related events.
* Location - to show where it's going to happen through Google Maps.
* Schedule - to show the agenda.
* Speakers - to list information about speakers.
* Sponsors - to show the brand of your sponsors.

It's important to change the `baseURL` property from `config.toml` file in order to reflect your settings.

### Google Maps

Google now requires a Google Maps JavaScript API Key to show maps. You can obtain your key [here](https://developers.google.com/maps/documentation/javascript/get-api-key). Then set your API key in the `gmap_api` param in the `config.toml` file.
