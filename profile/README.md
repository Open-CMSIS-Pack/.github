![Open-CMSIS-Pack](/profile/Open-CMSIS-Pack.png)

## About Open-CMSIS-Pack

The Open-CMSIS-Pack project offers a flexible and easy to use end to end development flow for embedded software - from project creation to software execution on real or virtual hardware.

## List of Repositories

### Specifications

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Open-CMSIS-Pack-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Spec) | A specification describing a delivery mechanism for software components, device parameters, and evaluation board support. It also defines the build tools for projects based on software packs. | Access the [pre-built specification directly](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/index.html). |
| [Open-CMSIS-Pack-Taxonomy](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Taxonomy) | Organizes Cclass and Cgroup definitions to access software [\<components\>](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/pdsc_components_pg.html) and application programming interfaces [\<apis\>](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/pdsc_apis_pg.html). | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Taxonomy) file. |
| [Open-CMSIS-CDI-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-CDI-Spec) | A set of APIs to enable firmware updates, running IoT applications, and RTOSes on a broad range of devices. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Open-CMSIS-CDI-Spec). |

### Ready-to-use Tools

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [CMSIS-Toolbox](https://github.com/Open-CMSIS-Pack/cmsis-toolbox) | A set of command-line tools for software packs. | The [documentation](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/README.md) explains the download, installation, and configuration process. |
| [gen-pack](https://github.com/Open-CMSIS-Pack/gen-pack) | A library for scripts creating Open-CMSIS-Packs. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack) file. |
| [gen-pack-action](https://github.com/Open-CMSIS-Pack/gen-pack-action) | A GitHub workflow action generating documentation and Open-CMSIS-Packs. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack-action). |
| [vidx2pidx](https://github.com/Open-CMSIS-Pack/vidx2pidx) | A package index generator. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/vidx2pidx). |

### CMSIS-Toolbox Project Examples (*csolution projects*)

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [csolution-examples](https://github.com/Open-CMSIS-Pack/csolution-examples) | A collection of exemplary csolution-based projects. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/csolution-examples). |
| [vscode-get-started](https://github.com/Open-CMSIS-Pack/vscode-get-started) | Setup of VS Code environment along wiht an example project. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/vscode-get-started). |

### Tutorials for Creating Own Software Packs (Webinar Recordings in Readme.md)

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Create-Scaleable-SW](https://github.com/Open-CMSIS-Pack/Create-Scalable-SW)   | Explains how to structure complex middleware stacks. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Create-Scalable-SW). |
| [SW-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/SW-Pack-HandsOn)   | Explains the steps to create a simple software pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/SW-Pack-HandsOn). |
| [DFP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn) | Explains the steps to create a device family pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn). |
| [BSP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn) | Explains the steps to create a board support pack. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn). |

### CMSIS Software Pack Examples

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [MDK-Middleware](https://github.com/ARM-software/MDK-Middleware) | Middelware for TCP/IP networking, File System, USB Device, USB Host with [reference applications](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/ReferenceApplications.md#mdk-middleware-reference-applications).| [User's Manual](https://arm-software.github.io/MDK-Middleware/latest/General/index.html) |
| [Sensor SDK](https://github.com/Open-CMSIS-Pack/Sensor-SDK-Example) | Example of sensor middelware using [reference applications with Arduino shields](https://github.com/ReinhardKeil/cmsis-toolbox/blob/main/docs/ReferenceApplications.md#sensor-reference-applications). | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/Sensor-SDK-Example). |
| [lwIP](https://github.com/Open-CMSIS-Pack/lwIP) | lwIP Network Stack. | . |
| [CMSIS-Driver_STM32](https://github.com/Open-CMSIS-Pack/CMSIS-Driver_STM32) | Shim layers convert STM32HAL to CMSIS-Driver for MDK Middleware. | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/CMSIS-Driver_STM32). |
| [NXP_iMXRT105x_MWP](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP) | NXP i.MXRT1051/1052 Device Series Middleware examples and CMSIS-Drivers Pack  | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP). |
| [NXP_IMXRT1050-EVKB_BSP](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP) | NXP IMXRT1050-EVKB Board Support Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP). |
| [STM32H7xx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7xx_DFP) | STMicroelectronics STM32H7 Series Device Family Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/STM32H7xx_DFP). |
| [STM32H743I-Eval_BSP](https://github.com/Open-CMSIS-Pack/STM32H743I-EVAL_BSP) | STMicroelectronics STM32H743I-Eval Board Support Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/STM32H743I-EVAL_BSP). |
| [STM32U5xx_DFP](https://github.com/Open-CMSIS-Pack/STM32U5xx_DFP) | STMicroelectronics STM32U5 Series Device Family Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/STM32U5xx_DFP). |
| [ST_B-U585I-IOT02A_BSP](https://github.com/Open-CMSIS-Pack/ST_B-U585I-IOT02A_BSP) | STMicroelectronics ST_B-U585I-IOT02A Board Support Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/ST_B-U585I-IOT02A_BSP). |
| [STM32H7RSxx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7RSxx_DFP) | STMicroelectronics STM32H7RS Series Device Family Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/STM32H7RSxx_DFP). |
| [STM32H7S78-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H7S78-DK_BSP) | STMicroelectronics STM32H7S78-DK Board Support Pack | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/STM32H7S78-DK_BSP). |

### Tools Source Code

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [devtools](https://github.com/Open-CMSIS-Pack/devtools) | Development repo of these command line tools: [packchk](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packchk), [packgen](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packgen), csloution ([projmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/projmgr)), and cbuild ([buildmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/buildmgr)). | Contains the specification of the [csolution project format](https://github.com/Open-CMSIS-Pack/devtools/blob/main/tools/projmgr/docs/Manual/Overview.md) and related files. |
| [cpackget](https://github.com/Open-CMSIS-Pack/cpackget) | Source code repository of the cpackget tool (part of the CMSIS-Toolbox) | Refer to [Readme.md](https://github.com/Open-CMSIS-Pack/cpackget). |



