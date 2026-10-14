# Drupal 11 Awesome CursorRules

This repository provides a custom **CursorRules** file tailored for Drupal 11 projects. The rules defined in the `.cursorrules` file ensure that AI-generated code adheres to Drupal 11’s coding standards, best practices, and modern architecture, leveraging PHP 8.3 or newer, Symfony 7, and Drupal’s APIs.

## Purpose

The goal of this project is to enable a consistent, secure, and efficient development experience by guiding AI tools (such as the Cursor AI editor or VS Code extensions) with Drupal-specific instructions. This helps ensure that all code suggestions are:
- Fully compatible with Drupal 11.
- Aligned with Drupal’s coding and performance standards.
- Designed using best practices in module, theme, and API development.

## Contents

- **`.cursorrules`**: Contains detailed instructions for AI behavior, including guidelines for code structure, naming conventions, Drupal API usage, theming, and security.
- **`README.md`**: Provides an overview of the project, installation instructions, and contribution guidelines.

## Installation

1. **Copy the Rule File:**  
   In the Drupal 11 project (the directory that contains `composer.json`), run `New Cursor Rule` from the command palette. Cursor saves an `.mdc` file under `.cursor/rules`. Copy this folder's `.cursorrules` contents into that file. If the copied text has no frontmatter, set the rule type to Always Apply.

2. **Enable in Cursor:**  
   Cursor loads project rules from `.cursor/rules`. Confirm the new rule is listed under Customize → Rules. [Cursor's rules help](https://cursor.com/help/customization/rules) marks a root `.cursorrules` file as legacy.

3. **Commit the Changes:**  
   Once added, commit the file to your repository so that the rules are shared with your entire development team.

## References

- [Awesome CursorRules on GitHub](https://github.com/PatrickJS/awesome-cursorrules)
- [Drupal 11 Documentation](https://www.drupal.org/docs/understanding-drupal)
- [Drupal Coding Standards](https://www.drupal.org/docs/develop/standards)

## Contributing

Contributions and improvements are welcome. If you have suggestions or enhancements, please open an issue or submit a pull request.

## License

This catalog entry is covered by the repository license. See the [LICENSE](../../LICENSE) file for more details.
