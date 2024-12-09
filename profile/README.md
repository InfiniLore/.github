# InfiniLore 📚

Welcome to the **InfiniLore** organization! We are dedicated to building a comprehensive system that allows writers and creators to manage detailed worldbuilding content and compile it into structured manuscripts for books or other creative works.

## About InfiniLore

InfiniLore aims to be a complete solution for worldbuilders and storytellers. Our tools will help you organize and connect your creative material in meaningful ways, making it easy to integrate world elements into your manuscripts.

### Planned Features

The following lists are features that are planned for the InfiniLore Website and their core functionality is to be implemented by the end of Q2 2025.  
When applicable, a link will also be provided to the issue/PR which implements the feature.

#### User-Facing Features

- **User Management**
    - [ ] Creation of user accounts:
        - [ ] Producer (writer): Creates stuff and can potentially sell their work to consumers or other producers.
        - [ ] Consumer (reader): Views and consumes content.
    - [ ] Third-party login integration (e.g., Google).

- **Worldbuilding Tools**
    - [ ] Core worldbuilding data:
        - [ ] **Lore Scopes**: Define where data is written, supporting multiple universes.
        - [ ] **Timelines**: Define events, eras, and other chronological structures.
        - [ ] **Entities**: Represent objects, locations, or abstract ideas.
            - [ ] Types include Actors (e.g., characters), Props, Collectives, Locations (2D/3D), Systems (e.g., star systems).
        - [ ] **Writing**: Includes snippets, manuscripts, maps, and 3D assets.
    - [ ] Markdown support for text editing and linking data.

- **Writing Tools**
    - [ ] Chapter and scene organization.
    - [ ] Exporting manuscripts in various formats (e.g., PDF, Word, Markdown).
    - [ ] Writing goals and progress tracking.
    - [ ] Custom templates for writing prompts and formatting.

- **Collaboration Features**
    - [ ] Project-specific chats for communication.
    - [ ] Commenting and notification systems.

- **Asset Management**
    - [ ] Upload, organize, and share assets like images, maps, and metadata.
    - [ ] Resizing assets for optimal usage in projects.

- **Search and Navigation**
    - [ ] Global search for quick access to data.
    - [ ] Filters and sorting for results based on tags, attributes, or categories.
    - [ ] Bookmark system for fast retrieval of important content.

- **Customization**
    - [ ] Create custom writing templates for assets, texts, worldbuilding, etc...
    - [ ] Adjust UI themes, layouts, and colors.
    - [ ] Dynamic field creation to add custom fields as needed.

- **Security and Privacy**
    - [ ] Granular permissions for users and collaborators.
    - [ ] Two-factor authentication (2FA) for enhanced security.
    - [ ] Audit logs to track user actions.

#### Technical Features

- [ ] JWT Authenticated REST API, built with FastEndpoints.
- [ ] Blazor web server hosting the client and API.
- [ ] Markdown-based data embedding.
- [ ] Dynamic role-based access control system.
- [ ] Advanced search indexing for faster queries.
- [ ] Integration with external services for OAuth and storage.

## Repositories

- ### [InfiniLore.cs](https://github.com/InfiniLore/infinilore.cs)
  The core Blazor-based web application, Wasm Client & FastEndpoints API, that provides the foundation for organizing worldbuilding material and creating manuscripts. This is the central part of the InfiniLore system.

## License

All repositories under the InfiniLore organization are licensed under the [GPLv3 License](LICENSE), ensuring the openness and freedom of the project.  
While the InfiniLore project is licensed under GPLv3, Anna retains all rights and copyright over the design of the InfiniLore logo, the application, and any other related assets. This does not, and will never, extend to the content users create using the InfiniLore system.

## Contributing

We welcome contributions and suggestions! As InfiniLore evolves, we invite developers, writers, and creators to join us in building a powerful platform for worldbuilding and storytelling. Feel free to participate in discussions, report issues, or submit pull requests.

---

Thank you for your interest in InfiniLore! Stay tuned as we continue to develop tools that empower creators to bring their worlds to life.
