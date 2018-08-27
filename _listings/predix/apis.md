---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Artifacts
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Analytics Catalog - Get the descriptive information of the artifacts corresponding
    to an analytic catalog entry.
  x-api-slug: apiv1cataloganalyticsidartifacts-get
  description: 'Returns the description information (type, description, etc.) for
    all artifacts associated with the given analytic catalog entry id. Note: it does
    not return the artifact file contents; use the download APIs to obtain an artifact
    file. An error is returned if the supplied analytic catalog entry id does not
    exist.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1cataloganalyticsidartifacts-get-openapi.md
- name: Analytics Catalog - Upload an artifact and attach it to an analytic catalog
    entry.
  x-api-slug: apiv1catalogartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an analytic catalog entry. The multipart MIME structure must have the catalog
    entry id tagged as 'catalogEntryId',  the file contents tagged as 'file',  the
    artifact type tagged as 'type', and  a description (under 1024 characters) tagged
    as 'description'. Artifact types can be any string.  Artifacts with the type 'executable'
    must contain the executable for the analytic.   An analytic can only have 1 artifact
    labelled as 'executable'(See the documentation for more information regarding
    these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifacts-post-openapi.md
- name: Analytics Catalog - Update an artifact by id.
  x-api-slug: apiv1catalogartifactsid-put
  description: 'Update an artifact in the catalog with the contents of the supplied
    multipart MIME structure. The multipart MIME structure may have any of the following:
    new file contents tagged as ''file'',  a new artifact type tagged as ''type'',
    and  a new description (under 1024 characters) tagged as ''description''. Artifact
    types can be any string.  Artifacts with the type ''executable'' must contain
    the executable for the analytic.   An analytic can only have 1 artifact labelled
    as ''executable'' (See the documentation for more information regarding these
    files.)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-put-openapi.md
- name: Analytics Catalog - Delete an artifact by id.
  x-api-slug: apiv1catalogartifactsid-delete
  description: Deletes the artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-delete-openapi.md
- name: Analytics Catalog - Download an artifact file by id.
  x-api-slug: apiv1catalogartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsidfile-get-openapi.md
- name: Analytics Catalog - Upload an artifact and attach it to an analytic catalog
    entry.
  x-api-slug: apiv1catalogartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an analytic catalog entry. The multipart MIME structure must have the catalog
    entry id tagged as 'catalogEntryId',  the file contents tagged as 'file',  the
    artifact type tagged as 'type', and  a description (under 1024 characters) tagged
    as 'description'. Artifact types can be any string.  Artifacts with the type 'executable'
    must contain the executable for the analytic.   An analytic can only have 1 artifact
    labelled as 'executable'(See the documentation for more information regarding
    these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifacts-post-openapi.md
- name: Analytics Catalog - Update an artifact by id.
  x-api-slug: apiv1catalogartifactsid-put
  description: 'Update an artifact in the catalog with the contents of the supplied
    multipart MIME structure. The multipart MIME structure may have any of the following:
    new file contents tagged as ''file'',  a new artifact type tagged as ''type'',
    and  a new description (under 1024 characters) tagged as ''description''. Artifact
    types can be any string.  Artifacts with the type ''executable'' must contain
    the executable for the analytic.   An analytic can only have 1 artifact labelled
    as ''executable'' (See the documentation for more information regarding these
    files.)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-put-openapi.md
- name: Analytics Catalog - Delete an artifact by id.
  x-api-slug: apiv1catalogartifactsid-delete
  description: Deletes the artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-delete-openapi.md
- name: Analytics Catalog - Download an artifact file by id.
  x-api-slug: apiv1catalogartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsidfile-get-openapi.md
- name: Analytics Catalog - Download an artifact file by id.
  x-api-slug: apiv1catalogartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsidfile-get-openapi.md
- name: Analytics Catalog - Delete an artifact by id.
  x-api-slug: apiv1catalogartifactsid-delete
  description: Deletes the artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-delete-openapi.md
- name: Analytics Catalog - Update an artifact by id.
  x-api-slug: apiv1catalogartifactsid-put
  description: 'Update an artifact in the catalog with the contents of the supplied
    multipart MIME structure. The multipart MIME structure may have any of the following:
    new file contents tagged as ''file'',  a new artifact type tagged as ''type'',
    and  a new description (under 1024 characters) tagged as ''description''. Artifact
    types can be any string.  Artifacts with the type ''executable'' must contain
    the executable for the analytic.   An analytic can only have 1 artifact labelled
    as ''executable'' (See the documentation for more information regarding these
    files.)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-put-openapi.md
- name: Analytics Catalog - Upload an artifact and attach it to an analytic catalog
    entry.
  x-api-slug: apiv1catalogartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an analytic catalog entry. The multipart MIME structure must have the catalog
    entry id tagged as 'catalogEntryId',  the file contents tagged as 'file',  the
    artifact type tagged as 'type', and  a description (under 1024 characters) tagged
    as 'description'. Artifact types can be any string.  Artifacts with the type 'executable'
    must contain the executable for the analytic.   An analytic can only have 1 artifact
    labelled as 'executable'(See the documentation for more information regarding
    these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifacts-post-openapi.md
- name: Analytics Framework - Get the descriptive information of the artifacts corresponding
    to an analytic catalog entry.
  x-api-slug: apiv1cataloganalyticsidartifacts-get
  description: 'Returns the description information (type, description, etc.) for
    all artifacts associated with the given analytic catalog entry id. Note: it does
    not return the artifact file contents; use the download APIs to obtain an artifact
    file. An error is returned if the supplied analytic catalog entry id does not
    exist.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1cataloganalyticsidartifacts-get-openapi.md
- name: Analytics Framework - Get the descriptive information of the orchestration
    artifacts corresponding to an orchestration configuration entry.
  x-api-slug: apiv2configorchestrationsidartifacts-get
  description: 'Returns the description information (type, description, etc.) for
    all orchestration artifacts associated with the given configuration entry id.
    Note: it does not return the orchestration artifact file contents; use the download
    APIs to obtain an artifact file. An error is returned if the supplied orchestration
    configuration entry id does not exist.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidartifacts-get-openapi.md
- name: Analytics Framework - Upload an artifact and attach it to an analytic catalog
    entry.
  x-api-slug: apiv1catalogartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an analytic catalog entry. The multipart MIME structure must have the catalog
    entry id tagged as 'catalogEntryId',  the file contents tagged as 'file',  the
    artifact type tagged as 'type', and  a description (under 1024 characters) tagged
    as 'description'. Artifact types can be any string.  Artifacts with the type 'executable'
    must contain the executable for the analytic.   An analytic can only have 1 artifact
    labelled as 'executable'(See the documentation for more information regarding
    these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifacts-post-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv1catalogartifactsid-put
  description: 'Update an artifact in the catalog with the contents of the supplied
    multipart MIME structure. The multipart MIME structure may have any of the following:
    new file contents tagged as ''file'',  a new artifact type tagged as ''type'',
    and  a new description (under 1024 characters) tagged as ''description''. Artifact
    types can be any string.  Artifacts with the type ''executable'' must contain
    the executable for the analytic.   An analytic can only have 1 artifact labelled
    as ''executable'' (See the documentation for more information regarding these
    files.)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-put-openapi.md
- name: Analytics Framework - Delete an artifact by id.
  x-api-slug: apiv1catalogartifactsid-delete
  description: Deletes the artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-delete-openapi.md
- name: Analytics Framework - Download an artifact file by id.
  x-api-slug: apiv1catalogartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsidfile-get-openapi.md
- name: Analytics Framework - Upload an artifact and attach it to an orchestration
    configuration entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Framework - Delete an orchestration artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-delete
  description: Delete the orchestration artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-delete-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by id.
  x-api-slug: apiv2configorchestrationsartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsidfile-get-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Framework - Upload an artifact and attach it to an analytic catalog
    entry.
  x-api-slug: apiv1catalogartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an analytic catalog entry. The multipart MIME structure must have the catalog
    entry id tagged as 'catalogEntryId',  the file contents tagged as 'file',  the
    artifact type tagged as 'type', and  a description (under 1024 characters) tagged
    as 'description'. Artifact types can be any string.  Artifacts with the type 'executable'
    must contain the executable for the analytic.   An analytic can only have 1 artifact
    labelled as 'executable'(See the documentation for more information regarding
    these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifacts-post-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv1catalogartifactsid-put
  description: 'Update an artifact in the catalog with the contents of the supplied
    multipart MIME structure. The multipart MIME structure may have any of the following:
    new file contents tagged as ''file'',  a new artifact type tagged as ''type'',
    and  a new description (under 1024 characters) tagged as ''description''. Artifact
    types can be any string.  Artifacts with the type ''executable'' must contain
    the executable for the analytic.   An analytic can only have 1 artifact labelled
    as ''executable'' (See the documentation for more information regarding these
    files.)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-put-openapi.md
- name: Analytics Framework - Delete an artifact by id.
  x-api-slug: apiv1catalogartifactsid-delete
  description: Deletes the artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-delete-openapi.md
- name: Analytics Framework - Download an artifact file by id.
  x-api-slug: apiv1catalogartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsidfile-get-openapi.md
- name: Analytics Framework - Upload an artifact and attach it to an orchestration
    configuration entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Framework - Delete an orchestration artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-delete
  description: Delete the orchestration artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-delete-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by id.
  x-api-slug: apiv2configorchestrationsartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsidfile-get-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by id.
  x-api-slug: apiv2configorchestrationsartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsidfile-get-openapi.md
- name: Analytics Framework - Delete an orchestration artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-delete
  description: Delete the orchestration artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-delete-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Framework - Upload an artifact and attach it to an orchestration
    configuration entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Framework - Download an artifact file by id.
  x-api-slug: apiv1catalogartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsidfile-get-openapi.md
- name: Analytics Framework - Delete an artifact by id.
  x-api-slug: apiv1catalogartifactsid-delete
  description: Deletes the artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-delete-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv1catalogartifactsid-put
  description: 'Update an artifact in the catalog with the contents of the supplied
    multipart MIME structure. The multipart MIME structure may have any of the following:
    new file contents tagged as ''file'',  a new artifact type tagged as ''type'',
    and  a new description (under 1024 characters) tagged as ''description''. Artifact
    types can be any string.  Artifacts with the type ''executable'' must contain
    the executable for the analytic.   An analytic can only have 1 artifact labelled
    as ''executable'' (See the documentation for more information regarding these
    files.)'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifactsid-put-openapi.md
- name: Analytics Framework - Upload an artifact and attach it to an analytic catalog
    entry.
  x-api-slug: apiv1catalogartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an analytic catalog entry. The multipart MIME structure must have the catalog
    entry id tagged as 'catalogEntryId',  the file contents tagged as 'file',  the
    artifact type tagged as 'type', and  a description (under 1024 characters) tagged
    as 'description'. Artifact types can be any string.  Artifacts with the type 'executable'
    must contain the executable for the analytic.   An analytic can only have 1 artifact
    labelled as 'executable'(See the documentation for more information regarding
    these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv1catalogartifacts-post-openapi.md
- name: Analytics Runtime - Get the descriptive information of the orchestration artifacts
    corresponding to an orchestration configuration entry.
  x-api-slug: apiv2configorchestrationsidartifacts-get
  description: 'Returns the description information (type, description, etc.) for
    all orchestration artifacts associated with the given configuration entry id.
    Note: it does not return the orchestration artifact file contents; use the download
    APIs to obtain an artifact file. An error is returned if the supplied orchestration
    configuration entry id does not exist.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidartifacts-get-openapi.md
- name: Analytics Runtime - Upload an artifact and attach it to an orchestration configuration
    entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Runtime - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Runtime - Delete an orchestration artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-delete
  description: Delete the orchestration artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-delete-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by id.
  x-api-slug: apiv2configorchestrationsartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsidfile-get-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Runtime - Upload an artifact and attach it to an orchestration configuration
    entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Runtime - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Runtime - Delete an orchestration artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-delete
  description: Delete the orchestration artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-delete-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by id.
  x-api-slug: apiv2configorchestrationsartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsidfile-get-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by id.
  x-api-slug: apiv2configorchestrationsartifactsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsidfile-get-openapi.md
- name: Analytics Runtime - Delete an orchestration artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-delete
  description: Delete the orchestration artifact by artifact id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-delete-openapi.md
- name: Analytics Runtime - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Runtime - Upload an artifact and attach it to an orchestration configuration
    entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/artifacts/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---