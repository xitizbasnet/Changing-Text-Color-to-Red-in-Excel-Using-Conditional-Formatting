# Changing Text Color to Red in Excel Using Conditional Formatting

This guide explains how to change the text color of cells containing the value "No" to red in Microsoft Excel, while keeping the background color unchanged. 

## Steps to Change Text Color to Red

### 1. Select the Range
- Highlight the cells or columns where you have the "No" values (e.g., the cells with lift-related columns containing "No").

### 2. Use Conditional Formatting
- Go to the **Home** tab in Excel.
- In the **Styles** group, click on **Conditional Formatting**.
- Choose **New Rule** from the dropdown menu.

### 3. Set the Formula
- Select **Use a formula to determine which cells to format**.
- In the formula box, enter the following formula:

```excel
=A1="No"
```

> **Note:** Replace `A1` with the correct reference to your data range if it starts in a different cell. For example, if your range starts in cell B2, the formula would be `=B2="No"`.

### 4. Format the Text Color
- Click the **Format** button.
- In the **Format Cells** dialog box, go to the **Font** tab.
- Choose the **red** color for the text under the **Color** dropdown.
- Click **OK** to confirm your font color choice.

### 5. Apply the Rule
- Click **OK** again to apply the rule.

### Result:
Now, only the text (the word "No") will be colored red, and the background will remain unchanged.

---

## Example Use Case

This method is especially useful when you want to quickly highlight specific values (like "No") without affecting the background of the cells. It's commonly used in inventory lists, issue tracking sheets, or any data where a visual cue is needed to call attention to a particular status.

---

## Troubleshooting

- **No color change:** Ensure that the formula references the correct starting cell of your range. Double-check that the values are exactly "No" (case-sensitive).
- **Background color changes:** If your background color also changes, make sure the conditional formatting rule only applies to the font color, and that no additional formatting rules are applied.

---
