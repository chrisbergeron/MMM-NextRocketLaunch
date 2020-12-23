# MMM-NextRocketLaunch
Magic Mirror Module to display the Next Rocket Launch

## Installation
````
# Change into the MagicMirror modules directory
cd path/to/magicmirror/modules

# Clone this repo as a module
git clone https://github.com/chrisbergeron/MMM-NextRocketLaunch.git
````

![](example1.png)

To enable this module just add the following to the MagicMirror config file `config/config.js`:
```
{
	module: 'MMM-NextRocketLaunch',
	position: 'top_right',
	header: 'Next Rocket Launch',
},
```
# NOTE: If this is the only module in your MagicMirror configuration, you can omit the last comma (,).  Then reload MagicMirror.

To customize the appearance of the module, you can override the default values by editing the css/custom.css file:

```
/* MMM-NextRocketLaunch */
    .module.MMM-NetworkScanner {
        background-color:rgba(0,0,0,0.0);  
    }
```

Configuration Options:
| Option | Description |
| --- | --- |
| position | Where the module will appear.  Valid values are: `top_right`, `center`, `bottom_right` or any value that is supported by MagicMirror|
| header | The name of the header to display, or `null` to not display the module's header at all |

```javascript
{
	module: 'MMM-NextRocketLaunch',
	position: 'top_right',
	header: 'Next Rocket Launch',
},
```