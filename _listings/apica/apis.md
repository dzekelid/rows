---
name: Apica
x-slug: apica
description: Apicas performance testing and monitoring solutions provide critical
  peak performance data and 24/7 monitoring of applications and sites around the world.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
x-kinRank: "7"
x-alexaRank: "876355"
tags: Rows
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/apis.md
specificationVersion: "0.14"
apis:
- name: Browser Checks API Checks Browser
  x-api-slug: browser-checks-api
  description: Creates a new browser check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowser-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowser-post-openapi.md
- name: Browser Checks API Checks Browser
  x-api-slug: browser-checks-api
  description: Updates a browser check.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser/{checkId} '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowsercheckid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowsercheckid-put-openapi.md
- name: Browser Checks API Checks Browser Locations
  x-api-slug: browser-checks-api
  description: Gets a list of all locations that are available for browser checks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser/locations '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowserlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowserlocations-get-openapi.md
- name: Browser Checks API Checks Browser Results {resultId} URLdata?format={format}
  x-api-slug: browser-checks-api
  description: Gets a file that contains browser check result data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: ://///checks/browser/{checkId}/results/{resultId}/urldata
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowsercheckidresultsresultidurldata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowsercheckidresultsresultidurldata-get-openapi.md
- name: Browser Checks API Checks Browser Results URLdata
  x-api-slug: browser-checks-api
  description: Gets browser check results in json format by result ids.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: '://///checks/browser/{checkId}/results/urldata '
  tags: Browser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowsercheckidresultsurldata-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/checksbrowsercheckidresultsurldata-post-openapi.md
- name: Browser Checks API
  x-api-slug: browser-checks-api
  description: Apicas performance testing and monitoring solutions provide critical
    peak performance data and 24/7 monitoring of applications and sites around the
    world.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19004-apica.jpg
  humanURL: https://www.apicasystem.com
  baseURL: :///
  tags: Rows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rows/master/_listings/apica/openapi.md
x-common:
- type: x-blog
  url: https://www.apicasystem.com/blog/
- type: x-blog-rss
  url: https://www.apicasystem.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/apica
- type: x-developer
  url: http://api-wpm.apicasystem.com/v3/help
- type: x-documentation
  url: https://api-wpm.apicasystem.com/v3/Help
- type: x-email
  url: support@apicasystems.com
- type: x-email
  url: sales@apicasystems.com
- type: x-email
  url: swesales@apicasystems.com
- type: x-email
  url: operations@apicasystem.com
- type: x-github
  url: https://github.com/ApicaSystem
- type: x-linkedin
  url: https://www.linkedin.com/company/apica-ab
- type: x-phone
  url: 1 (310) 776-7540
- type: x-twitter
  url: https://twitter.com/apicasystems
- type: x-website
  url: https://www.apicasystem.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---