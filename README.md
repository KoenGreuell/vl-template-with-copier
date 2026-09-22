# {{ project_name or 'Project' }}

{{ description or "Short description goes here." }}

## Checklist

- Development plan: {{ 'Yes' if plan else 'No' }}
- Timeline: {{ 'Yes' if timeline else 'No' }}
- Codebase created: {{ 'Yes' if codebase else 'No' }}
- Version control: {{ 'Yes' if version_control else 'No' }}

_This README is rendered from the template's `copier.yml` answers._
