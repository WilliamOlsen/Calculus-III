---
layout: page
title: Course Notes
published: false
---

This page contains all of the course notes. 

## Chapter 13

|                | Notes            | Video discussions            |
|:---------------|:-----------------|:-----------------------------|
| `Section 13.1` | A pdf file       | Section 13.1: A YouTube link |
| `Section 13.2` | More practice    | A YouTube link               |

#### Interactive notebooks

Chapter 13 focuses on parametrized space curves, planes, and quadrics in three-space.

|        | Python notebook |
|:----------|:-------------------|
| `Parametrized curves` <br /> `in the plane`| Link to notebook.pynb |
| `something that's rather long and` <br /> `goes on for a very long time` | Another notebook.pynb |


## Chapter 14

|                | Notes            | Video discussions            |
|:---------------|:-----------------|:-----------------------------|
| `Section 13.1` | A pdf file       | Section 13.1: A YouTube link |
| `Section 13.2` | More practice    | A YouTube link               |

## Chapter 15

|                | Notes            | Video discussions            |
|:---------------|:-----------------|:-----------------------------|
| `Section 13.1` | A pdf file       | Section 13.1: A YouTube link |
| `Section 13.2` | More practice    | A YouTube link               |

## Chapter 16

|                | Notes            | Video discussions            |
|:---------------|:-----------------|:-----------------------------|
| `Section 13.1` | A pdf file       | Section 13.1: A YouTube link |
| `Section 13.2` | More practice    | A YouTube link               |

## Licenses

The license object accepts four fields regarding information about the licensing of your software and documentation.

```yaml
license:
  software: MIT License
  software_url: http://opensource.org/licenses/MIT

  docs: CC BY 3.0
  docs_url: http://creativecommons.org/licenses/by/3.0/
```

| Field          | Description                                                       |
|:---------------|:------------------------------------------------------------------|
| `software`     | The license the software is distributed under                     |
| `software_url` | A URL to the license text for the license specified in `software` |
| `docs`         | The license this documentation is distributed under               |
| `docs_url`     | A URL to the license text for the license specified in `docs`     |

## Links

The links object has two subobjects, `header` and `footer`; both of these objects accept an array of elements with a `title` and `url`. The links defined in the `header` object will appear in the navigation of the website and the links in the `footer` will appear at the bottom of the website.

```yaml
links:
  header:
    - title: GitHub
      url: https://github.com/allejo/jekyll-docs-theme
  footer:
    - title: GitHub
      url: https://github.com/allejo/jekyll-docs-theme
    - title: Issues
      url: https://github.com/allejo/jekyll-docs-theme/issues?state=open
```

| Field   | Description                           |
|:--------|:--------------------------------------|
| `title` | The textual representation of the URL |
| `url`   | The URL of the link                   |

## UI

The ui object will contain all the settings in regards to the aesthetics of the website

```yaml
ui:
  header:
    color1: "#080331"
    color2: "#673051"
    trianglify: true
```

| Field               | Description                                                               |
|:--------------------|:--------------------------------------------------------------------------|
| `color1` & `color2` | The two colors that will create the gradient of the page header           |
| `trianglify`        | When set to true, the page header will be a generated triangular pattern  |

## Analytics

```yaml
analytics:
    google: UA-123456-1
```

| Field    | Description                                                                   |
|:---------|:------------------------------------------------------------------------------|
| `google` | The unique identifier for Google Analytics; typically looks like `U-123456-1` |

## Social

Options for configuring buttons to "like", "tweet" or "star" this site with the respective social media websites.

```yaml
social:
  github:
    user: allejo
    repo: jekyll-docs-theme
  twitter:
    enabled: false
    via:
    hash:
    account:
  facebook:
    enabled: false
    profileUrl:
```
