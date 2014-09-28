# mysettings-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['mysettings']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### mysettings::default

Include `mysettings` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[mysettings::default]"
  ]
}
```
edit sample for Vgrantfile
```json
    chef.json = {
      mysettings: {
        hosts_ip: "192.168.1.137" 
      }
    }
    chef.run_list = %w[
      recipe[mysettings]
    ]
```


## License and Authors

Author:: YOUR_NAME (<YOUR_EMAIL>)
