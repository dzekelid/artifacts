---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Edit a comment added by the same user,
    on the given artifact id
  version: 1.0.0
  description: Edit a comment added by the same user, on the given artifact id.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /objects/{artifactId}/comments/{commentId}/edit:
    post:
      summary: Edit a comment added by the same user, on the given artifact id
      description: Edit a comment added by the same user, on the given artifact id.
      operationId: editComment
      x-api-path-slug: objectsartifactidcommentscommentidedit-post
      parameters:
      - in: path
        name: artifactId
        description: Artifact id
      - in: body
        name: body
        description: Comment
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: commentId
        description: Comment id
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Comment
      - Added
      - By
      - Same
      - User
      - ""
      - "On"
      - Given
      - Artifact
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