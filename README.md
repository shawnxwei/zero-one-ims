# Zero One IMS

A full-stack inventory management system for purchasing, sales, warehouse operations, and financial workflows.

## Overview

Zero One IMS is designed for small and medium-sized businesses that need a reliable system to manage purchasing, sales, inventory, warehouses, payments, and operational data.

The system connects inventory workflows with accounting processes and helps teams maintain consistent stock data across daily operations.

## Core Features

- Purchasing and supplier management
- Sales and order management
- Inventory and warehouse management
- Role-based data and feature permissions
- Inventory replenishment support
- Product price history
- Multi-batch inventory cost calculation
- Automatic accounting document generation
- Operational monitoring and business dashboards

## Architecture

The project uses a microservice-oriented architecture built around the Spring Cloud Alibaba ecosystem.

![System Architecture](docs/images/image-20260427180101728.png)

## Project Structure

```text
zero-one-ims/
├── psi-java/       # Java backend services
├── psi-frontend/   # Vue frontend
└── documents/      # Project and development documentation
```

## Technology Stack

### Backend

- Java
- Spring Boot
- Spring Cloud
- Spring Cloud Alibaba
- Spring MVC
- MyBatis
- MyBatis Plus
- MySQL
- Redis
- Sentinel
- Seata
- JWT

### Frontend

- Vue 3
- Element Plus
- JavaScript / TypeScript

## Service Design

The backend is organized around independent business services and shared infrastructure components.

![Service Overview](docs/images/image-20260427180158228.png)

![Business Architecture](docs/images/image-20260427180222600.png)

## Business Modules

- Purchasing management
- Inventory management
- Warehouse management
- Sales management
- Payment management
- Product and supplier data
- Business monitoring
- Financial document generation

![Purchasing Management](docs/images/image-20260427180241504.png)

![Inventory Management](docs/images/image-20260427180258804.png)

![Sales Management](docs/images/image-20260427180317562.png)

![Warehouse Management](docs/images/image-20260427180352272.png)

![Business Monitoring](docs/images/image-20260427180408631.png)

## Project Goals

- Keep inventory data consistent across business workflows
- Reduce repetitive operational work
- Support modular business services
- Improve visibility into purchasing, sales, and inventory
- Connect inventory management with financial processes
