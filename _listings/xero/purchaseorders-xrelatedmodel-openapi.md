---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting X-related-model Purchaseorders
  description: X-related-model purchaseorders.
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
    post:
      summary: Post Purchaseorders
      description: Post purchaseorders.
      operationId: postPurchaseorders
      x-api-path-slug: purchaseorders-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: PurchaseOrders
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
    put:
      summary: Put Purchaseorders
      description: Put purchaseorders.
      operationId: putPurchaseorders
      x-api-path-slug: purchaseorders-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: PurchaseOrders
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - PurchaseOrders
    x-related-model:
      summary: X-related-model Purchaseorders
      description: X-related-model purchaseorders.
      operationId: x-related-modelPurchaseorders
      x-api-path-slug: purchaseorders-xrelatedmodel
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