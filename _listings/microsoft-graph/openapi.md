---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/rows:
    get:
      summary: List Rows
      description: List rows Retrieve a list of tablerow objects.
      operationId: ListRows
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtrows-get
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
---