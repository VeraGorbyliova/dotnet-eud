---
title: Conditionally Change a Control's Appearance
author: Anna Gubareva
---
# Conditionally Change a Control's Appearance

This document describes how to change a report control's appearance based on a specific condition.

> [!NOTE]
> Use this approach if expressions **are enabled** in the Report Designer (the Label's smart tag includes the **Expression** property).
>
> ![](../../../../../images/eurd-label-expression-binding-modes.png)
>
> See the [Conditionally Change a Control's Appearance](../shape-data-data-bindings/conditionally-change-a-control-appearance.md) topic in the [Shape Data (Data Bindings)](../shape-data-data-bindings.md) section to learn about an alternative approach.

1. Switch to the [Report Explorer](../../report-designer-tools/ui-panels/report-explorer.md) and right-click the **Styles** category to create a new visual style.
	
	![](../../../../../images/eurd-win-shaping-create-new-report-style.png)

2. Right-click the created style and select **Edit Styles**.
	
	![](../../../../../images/eurd-win-shaping-edit-report-styles.png)

3. In the invoked **Styles Editor**, customize the created style's appearance settings.
	
	![](../../../../../images/eurd-win-shaping-customize-style-settings.png)

4. Create another style by cloning the existing one.
	
	![](../../../../../images/eurd-win-shaping-clone-a-style.png)

5. Customize the new style's appearance settings and close the editor.
	
	![](../../../../../images/eurd-win-shaping-cloned-style-settings.png)

6. Back in the Report Explorer, select a report element to which you wish to assign the created styles.
	
	![](../../../../../images/eurd-win-shaping-select-element-in-report-explorer.png)

7. Open the [Property Grid](../../report-designer-tools/ui-panels/property-grid.md)'s **Appearance** tab, click the **Style** property's marker and select **Style Expression** in the context menu.
	
	![](../../../../../images/eurd-win-shaping-style-name-expression-property.png)

8. In the invoked **Expression Editor**, specify the required condition for switching between the created styles.
	
	![](../../../../../images/eurd-win-shaping-style-name-expression.png)

Switch to [Print Preview](../../preview-print-and-export-reports.md) to view the resulting report.

![](../../../../../images/eurd-win-shaping-change-appearance-result.png)