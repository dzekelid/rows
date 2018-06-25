---
name: Browshot.com
x-slug: browshot-com
description: Browshot is a service to take screenshot of web pages. Use any of our
  mobile and desktop browsers. We provide a powerful API and libraries.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
x-kinRank: "7"
x-alexaRank: "1714303"
tags: Rows
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/browshot-com/apis.md
specificationVersion: "0.14"
apis:
- name: Browshot Get information about a browser
  x-api-slug: browshot
  description: Get information about a browser.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com
  baseURL: https://api.browshot.com//api/v1//browser/info
  tags: Browser,Info
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/browshot-com/browserinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/browshot-com/browserinfo-get-openapi.md
- name: Browshot Get all browsers
  x-api-slug: browshot
  description: Get all browsers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com
  baseURL: https://api.browshot.com//api/v1//browser/list
  tags: Browser,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/browshot-com/browserlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/browshot-com/browserlist-get-openapi.md
- name: Browshot
  x-api-slug: browshot
  description: 'A service to easily make screenshots of web pages in any screen size,
    as any device: iPhone, iPad, Android, Nook, PC, etc. Test your site on different
    devices in many resolutions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/717-browshot-com.jpg
  humanURL: http://browshot.com
  baseURL: https://api.browshot.com//api/v1
  tags: Rows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/browshot-com/openapi.md
x-common:
- type: x-base
  url: https://api.browshot.com/api/
- type: x-blog
  url: http://blog.browshot.com/
- type: x-blog-rss
  url: http://blog.browshot.com/feeds/posts/default
- type: x-crunchbase
  url: http://www.crunchbase.com/company/browshot
- type: x-crunchbase
  url: https://crunchbase.com/organization/browshot
- type: x-developer
  url: http://browshot.com/api/documentation
- type: x-email
  url: feedback@browshot.com
- type: x-twitter
  url: https://twitter.com/BrowshotCom
- type: x-website
  url: http://browshot.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---