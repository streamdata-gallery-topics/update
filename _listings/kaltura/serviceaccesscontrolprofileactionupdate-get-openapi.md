---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Access Controlprofile Action Update
  description: Update access control profile by id
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/accesscontrol/action/update:
    get:
      summary: Get Service Access Control Action Update
      description: Update Access Control Profile by id
      operationId: accessControl.update
      x-api-path-slug: serviceaccesscontrolactionupdate-get
      parameters:
      - in: query
        name: accessControl[description]
        description: The description of the Access Control Profile
      - in: query
        name: accessControl[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`True if this Conversion Profile
          is the default'
      - in: query
        name: accessControl[name]
        description: The name of the Access Control Profile
      - in: query
        name: accessControl[restrictions]
      - in: query
        name: accessControl[systemName]
        description: System name of the Access Control Profile
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrol
      - Action
      - Update
  /service/accesscontrolprofile/action/update:
    get:
      summary: Get Service Access Controlprofile Action Update
      description: Update access control profile by id
      operationId: accessControlProfile.update
      x-api-path-slug: serviceaccesscontrolprofileactionupdate-get
      parameters:
      - in: query
        name: accessControlProfile[description]
        description: The description of the Access Control Profile
      - in: query
        name: accessControlProfile[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`True if this access control
          profile is the partner default'
      - in: query
        name: accessControlProfile[name]
        description: The name of the Access Control Profile
      - in: query
        name: accessControlProfile[rules]
      - in: query
        name: accessControlProfile[systemName]
        description: System name of the Access Control Profile
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrolprofile
      - Action
      - Update
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