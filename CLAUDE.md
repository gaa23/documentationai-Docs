# Documentation Guidelines

This project uses [Documentation.AI](https://documentation.ai) for publishing docs. When writing or editing documentation, follow these standards.

## Writing Principles

- Use clear, direct language with active voice and present tense
- Lead with the most important information
- Keep sentences short and scannable
- Avoid jargon; define technical terms on first use

## File Structure

- Pages require YAML frontmatter with `title` and `description`
- H1 is auto-generated from frontmatter; start content at H2
- Use `Steps` component for procedures instead of ordered lists

## Component Syntax

- All attributes use kebab-case (e.g., `param-type`, `default-open`)
- Boolean attributes: use strings `required="true"` or JSX `horizontal={true}`
- Cards need `title`, `href`, and optional `icon` attributes

## Code Examples

- All code examples must be complete and runnable
- Specify the language for every code block
- Test examples before including them

## This Project

This is the MyDose Documentation.AI docs repo. Documentation should cover:

- How the MyDose docs site is organized (navigation, sections, and content types)
- Authoring patterns and shared components for this docs system
- How product features, APIs, and workflows are documented for MyDose