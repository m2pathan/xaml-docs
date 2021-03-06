---
title: SDK Examples
page_title: SDK Examples
description: SDK Examples
slug: radimageeditor-sdk-examples
tags: sdk,examples
published: True
position: 2
---

# SDK Examples

The [Telerik XAML SDK repository](https://github.com/telerik/xaml-sdk/tree/master/) provides additional demos for most of the Telerik UI for {% if site.site_name == 'WPF' %}WPF{% endif %}{% if site.site_name == 'Silverlight' %}Silverlight{% endif %} controls. The examples demonstrate many specific user case scenarios, that might be really helpful. In this article you can find the complete list of all SDK examples for __RadImageEditor__.

## List of all RadImageEditor SDK examples:

{% if site.site_name == 'WPF' %}

* __[Custom UI](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/CustomUIRadImageEditor)__ -  Custom UI 
In this sample you can see how to create custom UI for RadImageEditor. A custom container for settings is implemented in a user control and set to be the image editor's ToolSettingsContainer.
* __[Custom watermark tool](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/CustomWatermarkTool)__ - The example shows how a custom tool can be build. A respective command and tool settings have been implemented as well and wired to work with RadImageEditorUI.
* __[Handle Tool Commit](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/HandleToolCommit)__ -  Handle Tool Commit 
The example demonstrates how you can manipulate with RadImageEditor by handling its ToolCommitting and ToolCommitted events.
* __[Localization](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/Localization)__ - The example shows how RadImageEditor along with the predefined UI of the control can be localized.
* __[First look](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/RadImageEditorUIFirstLook)__ -  First look 
The example demonstrates how to use the predefined UI of RadImageEditor - RadImageEditorUI, with all implemented editing tools. It also shows how to load a file in the image editor.
{% endif %}
{% if site.site_name == 'Silverlight' %}
* __[Custom UI](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/CustomUIRadImageEditor)__ -  Custom UI 
In this sample you can see how to create custom UI for RadImageEditor. A custom container for settings is implemented in a user control and set to be the image editor's ToolSettingsContainer.
* __[Custom watermark tool](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/CustomWatermarkTool)__ - The example shows how a custom tool can be build. A respective command and tool settings have been implemented as well and wired to work with RadImageEditorUI.
* __[Handle Tool Commit](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/HandleToolCommit)__ -  Handle Tool Commit 
The example demonstrates how you can manipulate with RadImageEditor by handling its ToolCommitting and ToolCommitted events.
* __[Localization](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/Localization)__ - The example shows how RadImageEditor along with the predefined UI of the control can be localized.
* __[First look](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/RadImageEditorUIFirstLook)__ -  First look 
The example demonstrates how to use the predefined UI of RadImageEditor - RadImageEditorUI, with all implemented editing tools. It also shows how to load a file in the image editor.
* __[RadUpload integration](https://github.com/telerik/xaml-sdk/tree/master/ImageEditor/RadUploadIntegration)__ - 
This examples shows how a custom Save command can be created and wired with the UI, so that instead of saving files on the client machine, the user can upload them to the server through RadUpload.
{% endif %}

>You can also check the [SDK Samples Browser]({%slug sdk-samples-browser%}) that provides a more convenient approach in exploring and executing the examples in the Telerik XAML SDK repository. The SDK Samples Browser application is available for download from [this link](http://demos.telerik.com/xaml-sdkbrowser/).