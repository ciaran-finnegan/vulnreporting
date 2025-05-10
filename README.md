# Vulnerability Reporting & Metrics Platform

A centralized vulnerability management metrics platform that ingests vulnerability data from scanning tools, calculates standardized metrics, and provides dashboards for various stakeholders.

## Overview

This platform enables security teams to:
- Track vulnerability metrics across the organization
- Meet compliance requirements for multiple frameworks
- Generate executive dashboards and operational reports
- Provide consistent metrics for different stakeholders

## Key Features

- **Data Collection**: Automated collection from vulnerability scanners (starting with Nessus)
- **Metric Calculation**: Configurable metrics via YAML definitions
- **Framework Mapping**: Maps metrics to frameworks (CIS, ISO 27001, NIST, etc.)
- **API-First Design**: RESTful API and OData endpoints for BI integration
- **Role-Based Access**: Different views for technical teams and executives

## Documentation

For the detailed application design and technical specification see:
[Platform Specification (GitHub Wiki)](https://github.com/ciaran-finnegan/vulnreporting/wiki/Platform-Specification)

## Development

### Prerequisites
- Docker and Docker Compose
- Python 3.9+
- Node.js 16+

### Quick Start
1. Clone the repository
   ```bash
   git clone https://github.com/ciaran-finnegan/vulnreporting.git
   cd vulnreporting
   ```

2. Run the development environment
   ```bash
   docker-compose up
   ```

3. Access the application
   - API: http://localhost:8000/api/v1/
   - Frontend: http://localhost:3000/
