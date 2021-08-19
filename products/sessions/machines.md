---
description: Choice of machines  for Sessions
---

# Machines

Here are the machines you can use to start up sessions.

```text
grid session create --instance_type 8_v100_32gb
```

| Name | Accelerator type |
| :--- | :--- |
| 8\_V100\_32gb | V100 |
| 8\_V100\_16gb | V100 |
| 8\_T4\_16gb | T4 |
| 8\_K80\_12gb | K80 |
| 4\_V100\_16gb | V100 |
| 4\_T4\_16gb | T4 |
| 4\_M60\_8gb | M60 |
| 2\_M60\_8gb | M60 |
| 1\_V100\_16gb | V100 |
| 1\_T4\_16gb | T4 |
| 1\_K80\_12gb | K80 |
| 1\_M60\_8gb | M60 |
| 2\_CPU\_8gb | CPU |
| 2\_CPU\_4gb | CPU |

You can also use the CLI command [instance-types](../products/global-cli-configs/cli-api/grid-instance-types.md) to list the configured instance types


**Note: A credit card needs to be added to use GPU machines**
