# NUNCHI Public Release

This repository contains the official public documentation for NUNCHI, an AI-driven relationship coaching service.

---

## System Architecture Overview

NUNCHI is designed as a distributed, asynchronous system to handle complex AI computational tasks efficiently:

- Frontend: Dart based interface for user interaction.
- API Server: FastAPI based coordination layer.
- AI Worker: Distributed Celery workers for inference tasks.
- Message Broker: Redis for task scheduling and state management.
- Shared Storage: Secure, S3-compatible temporary storage.

## Public Documentation

Detailed information regarding the platform is available in the following documents:

- [System Documentation](./DOCS.md)
- [API Usage Policy](./API_POLICY.md)
- [Security and Privacy Policy](./SECURITY.md)

---

Note: Development and deployment configuration files are managed within the backend directory. Refer to the internal documentation for build and orchestration instructions.

---

Copyright 2026 NUNCHI AI. All rights reserved.


