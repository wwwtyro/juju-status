# juju-status

## Examples

<img src="https://raw.githubusercontent.com/wwwtyro/juju-status/master/images/default.png" width='100%'>
<img src="https://raw.githubusercontent.com/wwwtyro/juju-status/master/images/options.png" width='100%'>

## Options

* service.charm
* service.exposed
* service.status
* unit.workload
* unit.juju
* unit.machine
* unit.ports
* unit.address
* unit.version
* unit.message
* machine.state
* machine.dns
* machine.instance
* machine.series
* relations

## Notes

* To use with `watch`, use `watch --color`.
* `juju-status` won't wrap. It truncate lines and adds `..` to the end to indicate there's more to see.
* Items will be ordered according the the order in which you provide arguments, hierarchically.
* Adding color definitions for items sucks right now. Open `juju-status` and edit the `colors` dict. Please open a pull request with your changes.
* I haven't tested this with IPv6 addresses. It might break.
