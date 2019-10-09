<!--
Copyright 2019 Adobe Systems Incorporated

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
Form Hidden (v3)
====
Hidden form field component written in HTL.

## Features
* Allows a form owner to add hidden data to the form

### Use Object
The Form Hidden component uses the `com.adobe.cq.wcm.core.components.models.form.Field` Sling Model for its Use-object.

### Edit Dialog Properties
The following properties are written to JCR for this Form Hidden component and are expected to be available as `Resource` properties:

1. `./id` - defines the identifier of this hidden field
2. `./name` - defines the name of the field, which will be submitted with the form data
3. `./value` - defines the value of the field, which will be submitted with the form data

## Information
* **Vendor**: Adobe
* **Version**: v3
* **Compatibility**: AEM 6.3
* **Status**: production-ready
* **Documentation**: [https://www.adobe.com/go/aem\_cmp\_form\_hidden\_v3](https://www.adobe.com/go/aem_cmp_form_hidden_v3)
