# PAMPT
Patient Appointment Management and Telemedicine Platform

### Core Project Architecture:

- **PAMPT.AppHost**: Serves as the central host, managing application startups and telemetry.  
- **PAMPT.Applications**: Handles application implementation and management, including commands, queries, DTOs, and mappers for each domain module; integrates various WebAPI services for consumption by PAMPT.WebUI and PAMPT.Mobile.  
- **PAMPT.Infrastructures**: Manages persistence, migrations, extensions, services, and database contexts.  
- **PAMPT.Domain**: Defines entities, enums, interfaces, behaviors, events, views, constants, and common utilities.  
- **PAMPT.WebUI**: Provides an interactive portal for managing patient appointments and the telemedicine platform.  