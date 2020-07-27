---
date: "2020-07-21T16:03:07+02:00"
title: "keptn configure bridge"
slug: keptn_configure_bridge
---
## keptn configure bridge

Configures the credentials for the Keptn Bridge

### Synopsis

Configures the credentials for the Keptn Bridge.

```
keptn configure bridge --user=<user> --password=<password> [flags]
```

### Examples

```
keptn configure bridge --user=<user> --password=<password>
```

### Options

```
  -h, --help              help for bridge
  -o, --output            Print the current credentials
  -p, --password string   The password to login to the bridge
  -u, --user string       The user name to login to the bridge
```

### Options inherited from parent commands

```
      --mock                 mocking of server communication - ATTENTION: your commands will not be sent to the keptn server
  -q, --quiet                suppress debug and info output
      --suppress-websocket   disables websocket communication - use the ID of Keptn context (if provided) for checking the result of your command
  -v, --verbose              verbose logging
```

### SEE ALSO

* [keptn configure](../keptn_configure/)	 - Configures one of the specified parts of Keptn

###### Auto generated by spf13/cobra on 21-Jul-2020