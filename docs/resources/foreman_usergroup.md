
# foreman_usergroup


Usergroups can be used to organize permissions and ownership of the hosts.


## Example Usage

```
# Autogenerated example with required keys
resource "foreman_usergroup" "example" {
  admin = true
  name = "compute"
}
```


## Argument Reference

The following arguments are supported:

- `admin` - (Optional) Is an admin user group.
- `name` - (Required) Usergroup name.


## Attributes Reference

The following attributes are exported:

- `admin` - Is an admin user group.
- `name` - Usergroup name.

