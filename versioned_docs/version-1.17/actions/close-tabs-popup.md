---
id: close-tabs-popup
title: Close Tabs Popup
sidebar_label: Close Tabs Popup
---

> Audience: [`Citizen Developer`](audience.md#citizen-developers)
> 
> Skill Prerequisites: `Using Form Builder`

This action allows you to manually trigger a close Tabs action for the specified Form. Depending on the Action selected, the remaining actions will also execute.

## `Actions Covered by this Document`

| Action | Purpose |
| ------ | ------- |
| Close Tabs Popup And Continue Execution | Closes the specified Tabs popup and then continues to subsequent actions on the button and submission. |
| Close Tabs Popup And Stop Execution | Closes the specified Tabs popup and then stops further execution of both subsequent actions and HTTP Post submission. |

## `Input Parameter Reference`

| Parameter | Description | Supports Tokens | Default | Required |
| --------- | ----------- | --------------- | ------- | -------- |
| Select Module | Select the Tabs for which you want to trigger a close popup action. Optionally, click the `EXPR` button to tokenize the selection of the Tabs ID | Yes | Empty String | No |
