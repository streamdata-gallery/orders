---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting Get Purchaseorders
  description: Get purchaseorders.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /PurchaseOrders:
    get:
      summary: Get Purchaseorders
      description: Get purchaseorders.
      operationId: getPurchaseorders
      x-api-path-slug: purchaseorders-get
      parameters:
      - in: query
        name: DateFrom
      - in: query
        name: DateTo
      - in: query
        name: No Name
      - in: query
        name: Status
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
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