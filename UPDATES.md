- **0.0.1**
    - Microsgen first launch
    - Ability to generate DTOs, Service & Tests for new project
- **0.0.2**
    - Fixed bug with generating Service & Tests correctly
    - rename /dtoMapper to /mapper
    - private contructor in DTO mappers
- **0.1.0**
    - Ability to run generator for exact model
    - In controller tests use DateTimeFormatter only when necessary
    - Removed interfaces for services
    - Handler for Exception.class in ControllerAdvice
    - Added pagination for getAll() method
    - Fixed all imports. SonarQube gives no remarks
    - Fixed bug with List/Set/Collection in static objects in tests
    - Mapper uses only existing DTOs. 
    - Controller creates only when all DTOs are present
- **0.1.1**
    - Ability to generate DTO Mappers separately
    - Timestamp in the exception payload
    - Fixed issues with Linux/Unix systems