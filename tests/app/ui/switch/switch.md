---
nav-title: "switch How-To"
title: "switch"
description: "Examples for using switch"
previous_url: /ApiReference/ui/switch/HOW-TO
---
# Switch
Using a switch requires the Switch module.
<snippet id='article-require-switch'/>
### Binding the Switch checked property and Button isEnabled property to a observable view-model property.
``` XML
<Page loaded="pageLoaded">
 <StackLayout orientation="vertical">
   {%raw%}<Switch checked="{{ someProperty }}" />
   <Button isEnabled="{{ someProperty }}" text="This is a Button!" />{%endraw%}
 </StackLayout>
</Page>
```
<snippet id='article-binding-switch-property'/>
### Creating a switch
<snippet id='article-create-switch'/>
### Setting the checked property of a switch
<snippet id='article-setting-checked-property'/>
### Binding checked property to a model
<snippet id='aricle-binding-checked-property'/>
