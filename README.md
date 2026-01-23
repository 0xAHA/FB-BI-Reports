# Fishbowl BI Reports Collection

A collection of custom BI Reports and themes for Fishbowl Inventory Management, designed to streamline common inventory operations and provide enhanced reporting capabilities.

## Table of Contents
- [Installation](#installation)
- [Report Index](#report-index)
- [Themes](#themes)

---

## Installation

### Prerequisites
- Fishbowl Inventory Management System
- Access to the Reporting > BI Editor menu

### Step 1: Install Styling Themes

The themes must be installed **first** before importing any reports, as the reports depend on these stylesheets.

1. In Fishbowl, open **Reporting > BI Editor** menu
2. Click **Import**
3. Select the theme file (`.json` format):
   - `fishbowl-theme-modern.css`
4. Ensure that you tick the **"Publish"** checkbox
5. Select appropriate **None/View/Edit** settings for each User Group
6. Click **OK**

Repeat for both theme files.

### Step 2: Import BI Reports

After themes are installed, import the desired report(s):

1. In Fishbowl, open **Reporting > BI Editor** menu
2. Click **Import**
3. Select the report's `.json` file
4. Ensure that you tick the **"Publish"** checkbox
5. Select appropriate **None/View/Edit** settings for each User Group
6. Click **OK**

### Step 3: Using Reports

To open a report:

1. Open the **Reporting** module
2. Select **BI Report**
3. Double-click the report in the list

**Tip:** Where available, use the **Instructions** flyout on the report for information about the report's purpose and usage.

---

## Themes

### fishbowl-theme-modern.css

Modern Bootstrap 5-based theme with enhanced UI components and responsive design.

**Used by:** PPP Pricing Validator, Default Parts Updater

---

## Notes

- Always install themes before importing reports
- Some reports include built-in Instructions flyouts with usage information
- Report documentation will be expanded as features are added

---

## Version History

See git commit history for detailed version information and changes.
