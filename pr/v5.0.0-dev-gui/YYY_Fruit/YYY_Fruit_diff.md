### New Endpoints: None
-----------------------

### Deleted Endpoints: None
---------------------------

### Modified Endpoints: 2
-------------------------
GET /fruit
- Responses changed
  - Modified response: 200
    - Content changed
      - Modified media type: application/json
        - Schema changed
          - Items changed
            - Property 'AllOf' changed
              - Schema #2 modified
                - Description changed from 'A JSON Schema G' to 'A JSON Schema I'
                - Properties changed
                  - New property: newFruitProperty1
                  - Deleted property: color

GET /fruit/{id}
- Responses changed
  - Modified response: 200
    - Content changed
      - Modified media type: application/json
        - Schema changed
          - Property 'AllOf' changed
            - Schema #2 modified
              - Description changed from 'A JSON Schema G' to 'A JSON Schema I'
              - Properties changed
                - New property: newFruitProperty1
                - Deleted property: color

