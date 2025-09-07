# S3 Pre-signed URL Generator Task Plan
## Overview
- **Goal**: Generate AWS S3 pre-signed URLs for uploads and downloads.
- **Components**: Angular frontend and Node/Express backend service

## Implementation Steps
### Frontend
1. Build form for bucket/key/expiration input and display signed URL

### Backend
1. Add server route `Tools/s3-presign/` using AWS SDK and env credentials

### Security & Performance
1. Sanitize user inputs and handle errors gracefully.
2. Log operations and expose metrics for monitoring.

### Testing
1. Unit tests for core logic.
2. Integration tests covering end-to-end scenarios.

### Deployment & Monitoring
1. Document usage in project README and add observability hooks.
