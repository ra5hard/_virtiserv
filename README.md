macos-latest
<img width="600" height="600" alt="ezgif com-resize" src="https://github.com/user-attachments/assets/c99cda5f-b95b-4542-acc3-1182ca9c7856" />

<img  alt="image" src="https://github.com/user-attachments/assets/61bafbcc-62c5-441d-b3f1-b01339713d3e" />

<img  alt="tumblr_35300d3bd6591f7bf5cc45653bf20532_52a1c7bf_1280" src="https://github.com/user-attachments/assets/2a53188a-e294-4874-906b-dd8d827a7f64" />
<img alt="ezgif com-gif-maker" src="https://github.com/user-attachments/assets/f4978247-4891-457d-b04b-886c15e40e78" />

<img alt="tumblr_8fbfbbeec24ccb1a42b7d0a9038e0bab_e4d210df_1280" src="https://github.com/user-attachments/assets/e74a27a0-de2f-43b1-b42c-6187ab1e7f84" />
<img   alt="tumblr_1366c97ddc23776db026ef34172efdda_070fa3c6_1280" src="https://github.com/user-attachments/assets/6fd93a7a-1b19-4743-b040-11d8aefd8ba2" />


[draperutah.gov/ @nasa-jpl](https://www.draperutah.gov/) //// [US, UT, Draper, 13997 S Minuteman Dr, 84020](https://earth.google.com/web/search/13997+S+Minuteman+Dr,+Draper,+UT+84020,+USA/@40.49809233,-111.88980478,1357.03085006a,190.11852343d,35y,149.35617348h,81.17454632t,360r/data=CiwiJgokCX7WD4fcYkFAEYDWD4fcYkHAGRS5DvugTUpAIRc2xq4v_E7AQgIIAUICCABKDQj___________8BEAA)
![https://www.draperutah.gov/media/35fctv0w/city-of-draper-logo-vector.svg](https://www.draperutah.gov/media/35fctv0w/city-of-draper-logo-vector.svg)

<img alt="tumblr_648cb4f6256a1817e35df27f49e941cd_165cec0c_1280" src="https://github.com/user-attachments/assets/80296ae4-0596-4369-9612-c6c6083cfa22" />


<img width="709" height="945" alt="IMG_20250714_084757_1" src="https://github.com/user-attachments/assets/c3550e48-6f1f-4936-ad8a-5e5eb94ea5d4" />

# The Architect theme

[![.github/workflows/ci.yaml](https://github.com/pages-themes/architect/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/architect/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-architect.svg)](https://badge.fury.io/rb/jekyll-theme-architect)

*Architect is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/architect), or even [use it today](#usage).*

![Thumbnail of Architect](thumbnail.png)

## Usage

To use the Architect theme:


1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: pages-themes/architect@v0.2.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Architect will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" (unquoted) to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. For some changes such as a custom `favicon`, you can add custom files in your local `_includes` folder. The files [provided with the theme](https://github.com/pages-themes/architect/tree/master/_includes) provide a starting point and are included by the [original layout template](https://github.com/pages-themes/architect/blob/master/_layouts/default.html).
2. For more extensive changes, [copy the original template](https://github.com/pages-themes/architect/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
3. Create a file called `/_layouts/default.html` in your site
4. Paste the default layout content copied in the first step
5. Customize the layout as you'd like

### Customizing Google Analytics code

Google has released several iterations to their Google Analytics code over the years since this theme was first created. If you would like to take advantage of the latest code, paste it into `_includes/head-custom-google-analytics.html` in your Jekyll site.

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/architect/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: http://example.com/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).

## Roadmap

See the [open issues](https://github.com/pages-themes/architect/issues) for a list of proposed features (and known issues).

## Project philosophy

The Architect theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Architect? We'd love your help. Architect is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/architect`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme


<img width="446" height="448" alt="LATRiCEFitZPATRiCKimages" src="https://github.com/user-attachments/assets/64ebd00a-d08a-4652-a62e-2c4732a89f1e" />
<img width="192" height="240" alt="LATRiCEFiTZPATRiCKimages1" src="https://github.com/user-attachments/assets/4f229e30-7a27-40ce-9e95-f473e264da3c" />
<img width="335" height="597" alt="LATRiCEViRTiSERVFiTZPATRiCKimages" src="https://github.com/user-attachments/assets/f8fcff6c-dafd-4e16-9438-a95d7f405ec4" />



### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.
