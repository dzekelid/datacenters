---
swagger: "2.0"
info:
  title: Akamai API Get a Data Center
  description: Get a Data Center
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
  /config-gtm/v1/domains/{domain}/datacenters/{datacenterId}:
    get:
      summary: Get a Data Center
      description: Get a Data Center
      operationId: configgtmv1domainsdomaindatacentersdatacenterid
      parameters:
      - in: query
        name: datacenterId
        description: Numeric id of the data center
        type: string
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - gtm
      - domains
      - datacenters
      - datacenter
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