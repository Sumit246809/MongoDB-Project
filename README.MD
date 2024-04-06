## Data Model Overview

When designing a data model for resource allocation in the manufacturing industry, it's essential to consider various aspects. Here's a high-level overview of five collections and their respective fields:

### 1. Resource Collection:
- **Resource ID**: A unique identifier for each resource (e.g., machine, workstation, operator).
- **Resource Type**: Categorization (e.g., CNC machine, assembly line, forklift).
- **Capacity**: Maximum workload the resource can handle.
- **Availability Schedule**: Time slots when the resource is available for allocation.

### 2. Order Collection:
- **Order ID**: Unique identifier for production orders.
- **Product Type**: The type of product being manufactured.
- **Quantity**: Number of units required.
- **Due Date**: Deadline for completing the order.

### 3. Allocation Collection:
- **Allocation ID**: Unique identifier for resource allocations.
- **Resource ID**: Links to the allocated resource.
- **Order ID**: Links to the production order.
- **Start Time**: When the resource allocation begins.
- **End Time**: When the resource allocation ends.

### 4. Performance Metrics Collection:
- **Cycle Time**: Time taken to complete one production cycle.
- **Utilization**: Resource usage efficiency (actual vs. available time).
- **Downtime**: Duration when the resource is idle.
- **Throughput**: Number of completed orders per unit time.

### 5. Maintenance Collection:
- **Maintenance ID**: Unique identifier for maintenance tasks.
- **Resource ID**: Links to the resource requiring maintenance.
- **Maintenance Type**: Scheduled or unscheduled.
- **Maintenance Date**: When maintenance occurred.
- **Maintenance Details**: Description of the maintenance performed.
