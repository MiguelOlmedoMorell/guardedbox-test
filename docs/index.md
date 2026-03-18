site_name: GuardedBox Documentation Test
site_description: GuardedBox Documentation Test

theme:
  name: gitbook
  features:
    - navigation.tabs
    - navigation.sections
    - toc.integrate
    - content.code.copy

repo_url: https://github.com/miguelolmedomorell/portfolio
repo_name: miguelolmedomorell/portfolio
edit_uri: edit/main/docs/

markdown_extensions:
  - admonition
  - pymdownx.details
  - pymdownx.superfences
  - pymdownx.highlight:
      anchor_linenums: true

nav:
  - Home: index.md
  - Technical documentation:
    - SAMPLE - Building a product creation POST endpoint in Spring Boot: technical-documentation/sample-tutorial.md
    - Markdown guide: technical-documentation/markdown-guide.md
    - What is the ASD-STE100 Simplified Technical English (STE)?: technical-documentation/asd-ste100.md
    - How to choose the right documentation platform: technical-documentation/doc-platform.md
    - Why your team needs a Technical Writer: technical-documentation/tech-writer.md
  - Academic essays & conferences: academic.md
  - Translations: translations.md
  - Press & media: press-media.md
  - 