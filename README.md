# Tide Media
Media types and related configurations for [Tide](https://github.com/dpc-sdp/tide) distribution for [Drupal 8](https://github.com/dpc-sdp)

Tide is a Drupal 8 distribution focused on delivering an API first, headless Drupal content administration site.

[![CircleCI](https://circleci.com/gh/dpc-sdp/tide_media.svg?style=shield&circle-token=2a0e49166724ac193636fba5b458024e00342dce)](https://circleci.com/gh/dpc-sdp/tide_media)
[![Release](https://img.shields.io/github/release/dpc-sdp/tide_media.svg)](https://github.com/dpc-sdp/tide_media/releases/latest)
![https://www.drupal.org/8](https://img.shields.io/badge/Drupal-8-blue.svg)
[![Licence: GPL 2](https://img.shields.io/badge/licence-GPL2-blue.svg)](https://github.com/dpc-sdp/tide_media/blob/master/LICENSE.txt)
[![Pull Requests](https://img.shields.io/github/issues-pr/dpc-sdp/tide_page.svg)](https://github.com/dpc-sdp/tide_media/pulls)

## What is in this package
- Media types: Document, Audio, Video, Embed Video, File
- Media entity fields: Department, License
- Entity browser configurations
- JSONAPI module integration

## Installation
To install this package, add this custom repository to `repositories` section of
your `composer.json`:

```json
{
  "repositories": {        
      "dpc-sdp/tide_media": {
          "type": "vcs",
          "no-api": true,
          "url": "https://github.com/dpc-sdp/tide_media.git"
      }
  }
}
```

Require this package as any other Composer package:
```bash
composer require dpc/tide_media 
``` 

## Support
[Digital Engagement, Department of Premier and Cabinet, Victoria, Australia](https://github.com/dpc-sdp) 
is a maintainer of this package.

## Contribute
[Open an issue](https://github.com/dpc-sdp) on GitHub or submit a pull request with suggested changes.

## Development and maintenance
Development is powered by [Dev-Tools](https://github.com/dpc-sdp/dev-tools). Please refer to Dev-Tools' 
page for [system requirements](https://github.com/dpc-sdp/dev-tools/#prerequisites) and other details.

To start local development stack:
1. Checkout this project 
2. Run `./dev-tools.sh`
3. Run `ahoy build`
 
## Related projects
- [tide](https://github.com/dpc-sdp/tide)       
- [tide_api](https://github.com/dpc-sdp/tide_api)         
- [tide_core](https://github.com/dpc-sdp/tide_core)
- [tide_event](https://github.com/dpc-sdp/tide_event)
- [tide_landing_page](https://github.com/dpc-sdp/tide_landing_page)
- [tide_monsido](https://github.com/dpc-sdp/tide_monsido) 
- [tide_news](https://github.com/dpc-sdp/tide_news)       
- [tide_page](https://github.com/dpc-sdp/tide_page)       
- [tide_search](https://github.com/dpc-sdp/tide_search)   
- [tide_site](https://github.com/dpc-sdp/tide_site)       
- [tide_test](https://github.com/dpc-sdp/tide_test)       
- [tide_webform](https://github.com/dpc-sdp/tide_webform)  

## License
This project is licensed under [GPL2](https://github.com/dpc-sdp/tide_media/blob/master/LICENSE.txt)
