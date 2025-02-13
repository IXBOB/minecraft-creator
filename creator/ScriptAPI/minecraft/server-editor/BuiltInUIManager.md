---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server-editor.BuiltInUIManager Interface
description: Contents of the @minecraft/server-editor.BuiltInUIManager class.
---
# BuiltInUIManager Interface

Represents a UI session for a given player

## Methods
- [navigateToDocumentation](#navigatetodocumentation)
- [navigateToFeedback](#navigatetofeedback)
- [navigateToPauseScreen](#navigatetopausescreen)
- [updateLogPanelVisibility](#updatelogpanelvisibility)
- [updateUISettingsPanelVisibility](#updateuisettingspanelvisibility)
- [updateWelcomePanelVisibility](#updatewelcomepanelvisibility)

### **navigateToDocumentation**
`
navigateToDocumentation(): void
`

Navigates to the documentation site.

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **navigateToFeedback**
`
navigateToFeedback(): void
`

Navigates to the feedback site

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **navigateToPauseScreen**
`
navigateToPauseScreen(): void
`

Navigates to the pause screen

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **updateLogPanelVisibility**
`
updateLogPanelVisibility(visibility: boolean): void
`

Updates the visibility of the log panel

#### **Parameters**
- **visibility**: *boolean*

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **updateUISettingsPanelVisibility**
`
updateUISettingsPanelVisibility(visibility: boolean): void
`

Updates the visibility of the control demo

#### **Parameters**
- **visibility**: *boolean*

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **updateWelcomePanelVisibility**
`
updateWelcomePanelVisibility(visibility: boolean): void
`

Updates the visibility of the welcome panel

#### **Parameters**
- **visibility**: *boolean*

#### **Returns** *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.
