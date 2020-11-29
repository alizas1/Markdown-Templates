# Proto Information 
The following is the content that should be provided per endpoint in the proto files:
## Endpoint / RPC / Function definition
- Summary: Single-line summary of function.
- Description: Multi-line description of function. 
  - Notes
  - Limitations
- Parameters 
  - Description
- Return 
  - Description (Corvid Only)
  - Note: Consider the difference between the request and response objects
- Errors: 
  - Generic: Codes (Provide full description below)
  - Non-generic: Code and description
    - Server errors
- Backend Event / Webhook 
  - Summary: what event causes it to fire?
  - Description: Multi-line description of event. 
    - Notes
    - Limitations
  - Parameters 
    - Description
    - Timestamp if not included in payload
- Entity / Object
  - Name
  - Type
  - Description
    - Notes
    - Limitations
    - Enum
    - Required/Optional