---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "validation_warnings Data Source - terraform-provider-validation"
subcategory: ""
description: |-
  Causes one or more warnings to be shown if the condition is true.
---

# validation_warnings (Data Source)

Causes one or more warnings to be shown if the condition is true.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `warning` (Block List, Min: 1) (see [below for nested schema](#nestedblock--warning))

### Read-Only

- `id` (String) The ID of this resource.

<a id="nestedblock--warning"></a>
### Nested Schema for `warning`

Required:

- `condition` (Boolean) The condition which, if true, causes a warning message to be printed.
- `summary` (String) The message displayed to the user if the condition is true.

Optional:

- `details` (String) More details about the message being displayed to the user, if any.