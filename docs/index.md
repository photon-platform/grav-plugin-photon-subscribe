<a href="https://photon-platform.net/">
    <img src="https://photon-platform.net/user/images/photon-logo-banner.png" alt="photon" title="photon" align="right" height="120" />
</a>


# photon ✴ Subscribe

## 0.1.0

---


> components for phpList config

- [configuration](#configuration)
- [templates](#templates)
- [scaffolds](#scaffolds)
- [scss](#scss)
- [assets](#assets)
- [languages](#languages)

# configuration
blueprints.yaml

fields:
- enabled
- built_in_css
- built_in_js
- account_id
- list_id

Before configuring this plugin, you should copy the `user/plugins/photon-subscribe/photon-subscribe.yaml` to `user/config/plugins/photon-subscribe.yaml` and only edit that copy.

Here is the default configuration and an explanation of available options:

```yaml
enabled: true
built_in_css: true
built_in_js: true

description: Custom Text added by the **photon-subscribe** plugin (disable plugin to remove)
```

Note that if you use the admin plugin, a file with your configuration, and named photon-subscribe.yaml will be saved in the `user/config/plugins/` folder once the configuration is saved in the admin.


# blueprints

```sh
blueprints
└── subscribe.yaml
```

### Subscribe
subscribe.yaml
extends: article
fields:
- header.subscribe
  - .notes

# templates

```sh
templates
├── _asides
│   └── mailchimp-signup.html.twig
└── subscribe.html.twig
```

# assets

```sh
assets
├── subscribe.css
└── subscribe.js
```


## Installation

- all photon plugins are installed as git submodules. More on that later.



## Configuration


## Usage

Select template type when creating a new page

## Credits


## To Do

- [ ] Future plans, if any


copyright &copy; 2020
