

| Item                   | Description                           | Type               | Example Value   | Extra Information                          |
| ---------------------- | ------------------------------------- | ------------------ | --------------- | ------------------------------------------ |
| zabbiz.system.name     | System Name from IEASYSxx             | Text               | S0W1            |                                            |
| zabbiz.zos.version     | z/OS VRM-level                        | Text               | 02.04           |                                            |
| zabbiz.sysplex.name    | Sysplex Name                          | Text               | ADCDPL          |                                            |
| zabbiz.jes2.primaryname| JES Info                              | Text               | JES2            |                                            |
| zabbiz.security.product| Security Product in use               | Text               | RACF            |                                            |
| zabbiz.srm.cpu.usage   | CPU Usage reported by SRM (CCVUTILP)  | Numeric (unsigned) | 3               |                                            |
| zabbiz.RCTLACS         | Long-term Average CPU Service Units   | Numeric (unsigned) | 0               |  https://www.ibm.com/docs/en/zos/2.4.0?topic=information-rct-mapping                                          |
| zabbiz.RCTIMGWU        | Workload Units available to MVS image | Numeric (unsigned) | 0               |  https://www.ibm.com/docs/en/zos/2.4.0?topic=information-rct-mapping                                         |
| zabbiz.RCTCECWU        | Workload Units capacity of CEC        | Numeric (unsigned) | 0               |  https://www.ibm.com/docs/en/zos/2.4.0?topic=information-rct-mapping                                           |
| zabbiz.cec.type        | The CEC Type :)                       | Text               | 1090-306 (ZPDT) |                                            |
| zabbiz.cec.serial      | CPU Serial                            | Text               | 001250          |                                            |
| zabbiz.cec,capacity    | Same as RCTCECWU?                     | Numeric (unsigned) | 17              |                                            |
| zabbiz.lpar.name       | Name of LPAR as defined in HMC        | Text               | PROD1           | For ZPDT it's the Instance User (IBMSYS1?) |
| zabbiz.lpar.capacity   | Capacity of LPAR                      | Numeric (unsigned) | 32              |                                            |
| zabbiz.vm.name         | Name of z/VM image                    | Text               | GUEST1          | Only available if running in a z/VM image  |
| zabbiz.vm.capacity     | Capacity of z/VM                      | Numeric (unsigned) | 32              | Only available if running in a z/VM image  |
