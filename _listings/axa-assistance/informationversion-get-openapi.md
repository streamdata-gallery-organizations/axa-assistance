---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Provide basic details about the current deployed version of
    the information API
  description: Provide basic details about the current deployed version of the information
    API
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assistance/version:
    get:
      summary: Provide basic details about the current deployed version of the assistance
        API
      description: Provide basic details about the current deployed version of the
        assistance API
      operationId: getAssistanceVersion
      x-api-path-slug: assistanceversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - assistance
      - API
  /information/version:
    get:
      summary: Provide basic details about the current deployed version of the information
        API
      description: Provide basic details about the current deployed version of the
        information API
      operationId: getInformationVersion
      x-api-path-slug: informationversion-get
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Provide
      - basic
      - detailAssistance
      - about
      - the
      - current
      - deployed
      - version
      - of
      - the
      - information
      - API
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