# Real State (Django Rest API)

## Endpoints
### Profiles:
    - api/v1/profile/me/                                  - Retrieve
    - api/v1/profile/update/                              - Update
    - api/v1/profile/agent/list/                          - List
    - api/v1/profile/top-agent/list/                      - List
### Property:
    - api/v1/property/list/                               - List
    - api/v1/property/agent/list/                         - List
    - api/v1/property/create/                             - Create
    - api/v1/property/detail/<slug:slug>/                 - Retrieve
    - api/v1/property/update/<slug:slug>/                 - Update
    - api/v1/property/delete/<slug:slug>/                 - Delete
    - api/v1/property/search/                             - List
### Rating:
    - api/v1/rating/<str:profile_id>/                     - Create
### Enquiry:
    - api/v1/enquiry/                                     - Create


# Run this project
`[sudo] docker-compose up --build`
