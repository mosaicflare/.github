# Mosaic Flare: Naming Conventions
Welcome to our Naming Convention Documentation. Adhering to a standardized naming convention is crucial for maintaining clarity, consistency, and efficiency across all our projects. By following these guidelines, we ensure that our codebase and repositories remain organized and easy to navigate, facilitating better collaboration and reducing misunderstandings. Consistent naming conventions also help in scaling our operations smoothly as we grow and expand. We appreciate your commitment to these standards, as they are foundational to our collective success and innovation.

## Groups
- **Core**: The Core group encompasses all fundamental services that form the backbone of our operations. These services are essential for the overall functionality and performance of our platform. Examples include authentication systems, data management, and other foundational services that support various applications and operations.
- **Personal**: The Personal group includes applications and services designed to enhance individual users' experiences. These apps are user-focused and aim to improve personal productivity, entertainment, or daily life. Examples include personal finance apps, lifestyle management tools, and individual productivity applications.
- **Business**: The Business group comprises applications and services tailored for business users. These apps are developed to support business operations, improve efficiency, and drive growth. Examples include CRM systems, project management tools, and business analytics platforms.
- **Government**: The Government group is dedicated to applications and services designed for governmental organizations and public sector entities. These apps aim to support public safety, administrative efficiency, and better service delivery to citizens. Examples include public safety management systems, emergency response tools, and governmental data analytics platforms.
- **Studios**: The Studios group focuses on gaming-related projects. These applications and services are dedicated to developing, managing, and distributing games. Examples include game development platforms, multiplayer gaming services, and game analytics tools.

## Categories
- **Microservices**: Microservices are modular, independent services that perform specific functions within a larger system. Each microservice is designed to handle a particular task and can be developed, deployed, and scaled independently. This category includes services like authentication, billing, notifications, and more.
- **Clients**: Clients are applications designed for end-users to interact with your services. These can be web-based, mobile, or desktop applications. The client category includes platforms and interfaces that users interact with directly, such as dashboards, mobile apps, and web applications.
- **Utilities**: Utilities are tools and scripts designed to support development and operational tasks. These can include data migration scripts, log parsers, monitoring tools, and other aids that streamline processes and enhance productivity.
- **Libraries**: Libraries consist of reusable code modules that can be shared across multiple projects. They provide common functionalities, such as authentication, UI components, and other shared services, to reduce duplication and maintain consistency.
- **Infrastructure**: Infrastructure repositories contain code and configurations for managing and deploying the technical infrastructure. This category includes CI/CD scripts, deployment configurations, and tools for automating and managing infrastructure.

## Guidelines
- Use hypens to separate the different parts of a name.
- Keep names concise but descriptive.
- Follow the pattern of `[category]-[group]-[name]`
- Use only the following short hand names for consistence:
    - Groups:
        - Core: `core`
        - Personal: `pers`
        - Business: `busn`
        - Government: `gvmt`
        - Studios: `stdo`
    - Categoreis:
        - Microservices: `micro`
        - Clients: `clnts`
        - Utilities: `utils`
        - Libraries: `libry`
        - Infrastructure: `infra`

## Examples
- **`micro-core-authentication`**: A core microservice focusing around 
- **`micro-stdo-connect4states`**: A studio microservice focusing on game states for the "Connect4" game
- **`clnts-gvmt-cad`**: A Government user client for Computer Aided Dispatch