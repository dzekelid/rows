---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Rows
  description: List rows Retrieve a list of tablerow objects.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/format/autofitRows:
    post:
      summary: Range Format Autofit Rows
      description: 'RangeFormat: autofitRows Changes the height of the rows of the
        current range to achieve the best fit, based on the current data in the columns.'
      operationId: RangeFormat:AutofitRows
      x-api-path-slug: workbooknamesltnamegtrangeformatautofitrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Rows
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitRows:
    post:
      summary: Range Format Autofit Rows
      description: 'RangeFormat: autofitRows Changes the height of the rows of the
        current range to achieve the best fit, based on the current data in the columns.'
      operationId: RangeFormat:AutofitRows
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatautofitrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Rows
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitRows:
    post:
      summary: Range Format Autofit Rows
      description: 'RangeFormat: autofitRows Changes the height of the rows of the
        current range to achieve the best fit, based on the current data in the columns.'
      operationId: RangeFormat:AutofitRows
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitrows-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Rows
  /workbook/tables(&lt;id|name&gt;)/rows:
    get:
      summary: List Rows
      description: List rows Retrieve a list of tablerow objects.
      operationId: ListRows
      x-api-path-slug: workbooktablesltidnamegtrows-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Rows
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---