---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Analytics Framework Get the descriptive information of the artifacts
    corresponding to an analytic catalog entry.
  version: 1.0.0
  description: 'Returns the description information (type, description, etc.) for
    all artifacts associated with the given analytic catalog entry id. Note: it does
    not return the artifact file contents; use the download APIs to obtain an artifact
    file. An error is returned if the supplied analytic catalog entry id does not
    exist.'
host: predix-acs.run.aws-usw02-pr.ice.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/catalog/analytics/{id}/artifacts:
    get:
      summary: Get the descriptive information of the artifacts corresponding to an
        analytic catalog entry.
      description: 'Returns the description information (type, description, etc.)
        for all artifacts associated with the given analytic catalog entry id. Note:
        it does not return the artifact file contents; use the download APIs to obtain
        an artifact file. An error is returned if the supplied analytic catalog entry
        id does not exist.'
      operationId: retrieveArtifactsByCatalogEntryId
      x-api-path-slug: apiv1cataloganalyticsidartifacts-get
      parameters:
      - in: path
        name: id
        description: analytic catalog entry id
      responses:
        2:
          description: Successful response
      tags:
      - Descriptive
      - Information
      - Of
      - Artifacts
      - Corresponding
      - To
      - Analytic
      - Catalog
      - Entry
  /api/v1/catalog/artifacts:
    post:
      summary: Upload an artifact and attach it to an analytic catalog entry.
      description: Upload a single artifact file in a multipart MIME structure and
        attach it to an analytic catalog entry. The multipart MIME structure must
        have the catalog entry id tagged as 'catalogEntryId',  the file contents tagged
        as 'file',  the artifact type tagged as 'type', and  a description (under
        1024 characters) tagged as 'description'. Artifact types can be any string.  Artifacts
        with the type 'executable' must contain the executable for the analytic.   An
        analytic can only have 1 artifact labelled as 'executable'(See the documentation
        for more information regarding these files.)
      operationId: uploadAnalyticArtifact
      x-api-path-slug: apiv1catalogartifacts-post
      parameters:
      - in: formData
        name: catalogEntryId
        description: (Required) analytic catalog entry id
      - in: formData
        name: description
        description: artifact description
      - in: formData
        name: file
        description: (Required) artifact file
      - in: formData
        name: type
        description: (Required) artifact type
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Artifact
      - Attach
      - It
      - To
      - Analytic
      - Catalog
      - Entry
  /api/v1/catalog/artifacts/{id}:
    put:
      summary: Update an artifact by id.
      description: 'Update an artifact in the catalog with the contents of the supplied
        multipart MIME structure. The multipart MIME structure may have any of the
        following: new file contents tagged as ''file'',  a new artifact type tagged
        as ''type'', and  a new description (under 1024 characters) tagged as ''description''.
        Artifact types can be any string.  Artifacts with the type ''executable''
        must contain the executable for the analytic.   An analytic can only have
        1 artifact labelled as ''executable'' (See the documentation for more information
        regarding these files.)'
      operationId: updateAnalyticArtifact
      x-api-path-slug: apiv1catalogartifactsid-put
      parameters:
      - in: formData
        name: description
        description: artifact description
      - in: formData
        name: file
        description: artifact file
      - in: path
        name: id
        description: artifact id
      - in: formData
        name: type
        description: artifact type
      responses:
        200:
          description: OK
      tags:
      - Artifact
      - By
      - Id
    delete:
      summary: Delete an artifact by id.
      description: Deletes the artifact by artifact id.
      operationId: deleteAnalyticArtifact
      x-api-path-slug: apiv1catalogartifactsid-delete
      parameters:
      - in: path
        name: id
        description: artifact id
      responses:
        200:
          description: OK
      tags:
      - Artifact
      - By
      - Id
  /api/v1/catalog/artifacts/{id}/file:
    get:
      summary: Download an artifact file by id.
      description: The file is downloaded as an octet-stream.
      operationId: downloadAnalyticArtifact
      x-api-path-slug: apiv1catalogartifactsidfile-get
      parameters:
      - in: path
        name: id
        description: artifact id
      responses:
        200:
          description: OK
      tags:
      - Download
      - Artifact
      - File
      - By
      - Id
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