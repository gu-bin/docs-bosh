# create_network

Creates a network that will be used to place VMs on.

## Arguments

* `network_definition` [Hash]: network_definition properties required for creating network. May contain range and gateway keys. Has to have cloud_properties - properties required for creating this network  specific to a CPI.


## Result

* network_info [Hash]: key has unique id of network, cloud_properties are properties required for placing VMs


## Examples

### API request





### Implementations

 * [cppforlife/bosh-warden-cpi-release](https://github.com/cppforlife/bosh-warden-cpi-release/blob/master/src/github.com/cppforlife/bosh-warden-cpi/action/attach_disk.go)


## Related

 * [create_disk V1](../cpi-api-v1-method/create-disk.md)
 * [detach_disk V1](../cpi-api-v1-method/detach-disk.md)
