---
swagger: "2.0"
info:
  title: Akamai API Modify a Stream
  description: Modify a Stream
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /config-media-live/v1/live/{domain}/stream/{streamId}:
    put:
      summary: Modify a Stream
      description: Modify a Stream
      operationId: configmedialivev1livedomainstreamstreamid
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - media
      - live
      - live
      - domain
      - stream
      - stream
definitions: []
x-collection-name: Akamai
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