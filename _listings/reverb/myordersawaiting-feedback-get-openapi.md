---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Get My Orders Awaiting Feedback
  description: List of orders that need feedback
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/orders/awaiting_feedback:
    get:
      summary: Get My Orders Awaiting Feedback
      description: List of orders that need feedback
      operationId: getMyOrdersAwaitingFeedback
      x-api-path-slug: myordersawaiting-feedback-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Orders
      - Awaiting
      - Feedback
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