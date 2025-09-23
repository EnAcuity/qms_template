# QMS Dynamic Traceability Demo

## Proof of Concept - Placeholder Data

This is a demonstration of a dynamic traceability system using **placeholder data only**.
All requirements shown are generic examples for demonstration purposes.

## Live Demo

View the live demo at: https://enacuity.github.io/qms_template/

## Structure

```
traceability/
├── user_needs/
│   └── UN-001.md          # Example User Need (Authentication)
└── product_requirements/
    ├── PRQ-001.md          # Example Requirement (Login)
    └── PRQ-008.md          # Example Requirement (Password)
```

## How It Works

1. **Markdown Files**: Each User Need and Product Requirement is a simple markdown file
2. **Links**: Requirements are cross-linked using standard markdown links
3. **Dynamic Loading**: The index.html uses JavaScript to fetch and parse the markdown files
4. **No Build**: Everything works directly in the browser - no compilation needed

## Key Features

- **Zero Build Process**: Works directly with GitHub Pages
- **Dynamic**: JavaScript reads markdown files at runtime
- **Linked**: Bi-directional links between needs and requirements
- **Expandable**: Easy to add more requirements

## Expanding the System

To use this for your own requirements:
1. Replace the placeholder UN-001.md with your actual user needs
2. Replace PRQ files with your actual requirements
3. Expand the JavaScript in index.html to read additional files as needed

**Note**: This repository contains only demonstration data with generic examples.