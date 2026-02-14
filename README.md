# Appian Atlas Power - UX Designer

UI/UX-focused view of Appian applications for designers who need to understand interfaces, user flows, and interaction patterns.

## What This Power Does

This power provides UI/UX-focused responses when exploring Appian applications through the Appian Atlas MCP server. Perfect for UX designers working on Appian solutions.

## Features

- **Interface focus**: Forms, views, dashboards, and UI components
- **SAIL components**: Shows relevant UI code and patterns
- **User flows**: Entry points, interactions, and journeys
- **Design patterns**: Identifies reusable UI patterns
- **Accessibility**: Evaluates accessibility features and gaps

## Installation

1. In Kiro IDE, go to the **Powers** tab
2. Click **Add Power**
3. Enter this URL:
   ```
   https://github.com/ram-020998/power-appian-atlas-ux-designer
   ```

## Prerequisites

You must have the **appian-atlas MCP server** installed. See the [gam-knowledge-base repository](https://github.com/ram-020998/gam-knowledge-base) for installation instructions.

## Other Personas

- **Developer**: [power-appian-atlas-developer](https://github.com/ram-020998/power-appian-atlas-developer) - Technical details and SAIL code
- **Product Owner**: [power-appian-atlas-product-owner](https://github.com/ram-020998/power-appian-atlas-product-owner) - Business-focused, no technical jargon

## Example Usage

```
User: "How does the Add Vendors action work?"

Response: "The Add Vendors form uses a standard form layout:

Layout Structure:
- Text field for vendor name (real-time validation)
- Email field with format validation
- Dropdown for category selection
- Text area for notes
- Primary 'Add Vendor' button and secondary 'Cancel' button

[Shows SAIL UI components]

User Flow:
1. User clicks 'Add Vendors' → Form appears
2. User enters information → Real-time validation
3. User clicks 'Add Vendor' → Submission
4. Success message appears

UX Patterns:
- Clear action hierarchy with button styling
- Helpful validation messages
- Keyboard navigation supported"
```

## License

MIT
