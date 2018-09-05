## Cheat Sheet (AWS EB CLI)
Created a cheat sheet to help with **AWS EB CLI** functionality

### Setup
Commands to help setup EB Environments
| command | summary |
|--|--|
| ```eb create``` | **Create** an EB environment |

### Deployment
Commands to help deploy to EB Environments
| command | summary |
|--|--|
| ```eb deploy``` | **Deploy** to EB enviroment using most recent ***commit*** |

### Monitoring
Commands to help watch / monitor your EB environment
| command | summary |
|--|--|
| ```eb open``` | **Open** environment in your browser |
| ```eb status``` | Show current **status** |
| ```eb health``` | Show current **health** |
| ```eb health --refresh``` | Show current **health** with ***10 second polling*** |
| ```eb events``` | Show all **events** |
| ```eb config``` | Show **config**uration options |
| ```eb logs``` | View content of **logs** of first instance |
| ```eb logs --all``` | View content of **logs** for ***all*** logs |
| ```eb logs --instance instanceName``` | View content of **logs** of named ***instance*** |

### Danger Area
Commands to help destroy EB Environments
| command | summary |
|--|--|
| ```eb terminate``` | **Terminate** EB enviroment |
