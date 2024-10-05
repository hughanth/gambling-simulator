# CSCI 265 Team Standards and Processes (Phase 2)

## Team name: Section 3

## Project/product name: Gambling Simulator

## Key contact person and email

 * Josiah Bowden, josiahbowden4@gmail.com *main contact*

## Documentation standards and processes
**Standards**:
* Use the [Markdown](https://www.markdownguide.org/basic-syntax/) format for internal documentation and project structure docs.
* For in-depth technical documentation, follow the [XML documentation format](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/xmldoc/) for C# code.
* Use appropriate comments in code for clarity.
* For grammar and style, use [Grammarly](https://www.grammarly.com/) or a built-in spell checker in your code editor (like Visual Studio’s editor tool or Microsoft Docs editor tool).

**Process**:
* Documentation for each module should include:
    * Purpose and functionality of the module.
    * How to use it (inputs/outputs).
    * Any limitations or known issues.
* Document code inline using XML comments in C#.

**Enforcement**:

* Each team member is responsible for documenting their code as they write it.
* Review sessions will be held to check the documentation of completed modules.

**Review Process**:

* All documentation changes go through the pull request process for review before merging.
* Use a “definition of done” checklist for documentation, ensuring:
    * Clear descriptions.
    * Consistent formatting.
    * Spelling and grammar checks.

## Coding standards and processes

**Standards**:
* Follow the [C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/identifier-names) as a baseline.
* Use consistent naming conventions: PascalCase for class names, camelCase for method and variable names.
* Always include access modifiers (e.g., `public`, `private`).
* Use meaningful variable and method names.

**Process**:
* All code changes will be done on the development branch and will require a mandatory code review before merging into the main branch.
* Every feature should have associated unit test where applicable.
* Use [Unity Test Framework](https://docs.unity3d.com/Packages/com.unity.test-framework@1.1/manual/index.html) for testing Unity scripts.

**Enforcement**:
* Peer code reviews are mandatory.
* Code cannot be merged into the main branch without at least one other team member reviewing and approving it.

**Review Process**:
* Reviews will be conducted by at least one team member on all pull requests (git Lead for example).
* Reviews focus on coding standards, test coverage, and adherence to architecture design.

## Version control standards and processes

**Repo Structure**:
* /src: Main source code for the project.
* /docs: All project documentation.
* /test: Unit and intergration tests.

**Branches**:
* Main: This is the production-ready branch. Only thoroughly tested and approved code will be merged here.
* Dev: Development branch for ongoing features and bug fixes.
* Feature branches: Each new feature or but fix will be developed in a separate branch.

**Commit Messages**:
* Use a consistent format for commit messages:
    * `feat`: for new features (e.g., `feat: add blackjack game mode`).
    * `fix`: for bug fixes (e.g., `fix: resolve game state reset issue`).
    * `docs`: for documentation changes.
    * `test`: for adding or improving tests.
    * `refactor`: for code refactoring without changing functionality.

**Tagging Releases**:
* Use semantic versioning (vX.Y.Z) for tagging releases (e.g., v1.0.0).

**Pull Requests**:
* Pull requests should be reviewed by at least one other team member.
* Include a summary of the changes, with references to any relevant issues or documentation.

**Enforcement**:
* Branch protection rules will be enforced on the main branch (e.g., code must pass all tests before merging).
* All team members must follow the commit message format and branching strategy.

**Review Process**:
* Weekly meetings will be held to review the state of the repository, making sure branches are kept clean and unused branches are deleted.
* A lead developer and git lead will be assigned to oversee the repository’s health and enforce version control rules.