# Repository Guidelines

## Project Structure

The root `README.md` is the GitHub profile page. It contains the profile introduction, tech stack, featured projects, and GitHub statistics. Badges, icons, and statistics images are embedded via external URLs. The repository currently has no application source, test directory, or local assets.

## Preview and Validation

The repository has no build command, local server, automated test suite, or coverage requirement. Use your editor's Markdown preview to check headings, tables, links, and images. For layout changes involving embedded HTML, verify the rendering on GitHub as well. Run `git diff --check` to catch whitespace errors in tracked changes. When editing badges or featured projects, open the modified links and verify the account names used in image URLs.

## Writing and Coding Style

Keep the default profile in Vietnamese (`README.md`) and its English translation in `README.en.md`. Update both versions when profile content changes. Write this guide in English. Preserve official names such as Java, Spring Boot, and React. Use Markdown for headings, lists, and tables. Match the indentation of adjacent HTML when editing badges or images. Use each project's actual name in the featured projects table. If Java code is added, follow Java and Spring Boot conventions and use JUnit and Mockito where appropriate.

## Commits and Pull Requests

The Git history starts with `Initial commit`. Use short commit subjects that describe the change, such as `Update profile project links`. In pull requests, describe what changed and how you checked it. Link the relevant issue when one exists and include a screenshot for visible layout changes.

## Agent Instructions

Reply in Vietnamese and keep technical terms in English. Cite code references as `file:line`. Use `ctx_execute` or `ctx_batch_execute` for large output such as logs, test results, and bulk reads. Ask before deleting files, running destructive commands, or changing public APIs. Never print or commit passwords, keys, or tokens.
