# ShipForge

A container deployment and release management platform for developers working with Docker-based applications.

ShipForge is intended to simplify application releases while maintaining visibility into builds, deployments, runtime health, and rollback operations.

## Planned Features

- Application and environment management
- Container image management
- Repository integration
- Automated build workflows
- Deployment configuration
- Release history
- Container health monitoring
- Deployment logs
- Rollback to previous releases
- Environment configuration management
- Deployment status dashboard

## Technology Stack

| Layer | Technology |
| --- | --- |
| Backend | Python, FastAPI |
| Frontend | React, TypeScript |
| Database | PostgreSQL |
| Containers | Docker |
| Reverse Proxy | Traefik |
| CI/CD | GitHub Actions |
| Infrastructure | Docker Compose |

## Architecture

ShipForge will use a control plane responsible for deployment configuration, release orchestration, and application state.

Build and deployment execution will be isolated from the management API.

Important engineering concerns include:

- Secure container execution
- Separation of control and execution privileges
- Build isolation
- Deployment state tracking
- Reproducible releases
- Safe rollback procedures
- Secret management
- Runtime health verification

The first version will target a controlled deployment environment rather than arbitrary multi-tenant infrastructure.

## Development Roadmap

- [ ] Define deployment architecture and security model
- [ ] Establish repository structure and CI
- [ ] Configure Docker and Makefile
- [ ] Implement application management
- [ ] Create deployment configuration model
- [ ] Implement container deployment execution
- [ ] Add deployment history
- [ ] Implement health checks
- [ ] Add logs and runtime status
- [ ] Implement rollback
- [ ] Complete security and failure testing

## Project Status

**Planning**

The project is in the architecture and requirements phase. Deployment features have not been implemented.

## License

License to be determined.