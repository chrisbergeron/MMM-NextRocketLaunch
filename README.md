# MMM-NextRocketLaunch
This is a Magic Mirror Module that displays the Next Rocket Launch from Earth.  The data comes from the excellent Launch Library 2 API provided by [thespacedevs](https://thespacedevs.com/llapi).  This is the Launch Library 2 [Documentation](https://launchlibrary.net/docs/1.4/api.html).

![NextRocketLaunch Module](example1.png)

## Installation
````bash
# Change into the MagicMirror modules directory
cd path/to/magicmirror/modules

# Clone this repo as a module
git clone https://github.com/chrisbergeron/MMM-NextRocketLaunch.git
````

To enable this module just add the following to the MagicMirror config file `config/config.js`:
```javascript
{
	module: 'MMM-NextRocketLaunch',
	position: 'top_right',
	header: 'Next Rocket Launch',
},
```
**NOTE**: If this is the only module in your MagicMirror configuration, you can omit the last comma (,).


Next just reload MagicMirror:
```bash
npm start run
```

To customize the appearance of the module, you can override the default CSS values by editing the `css/custom.css` file:

```css
/* MMM-NextRocketLaunch */
.module.MMM-NetworkScanner {
        background-color:rgba(0,0,0,0.0);  
    }
```

### Configuration Options:
| Option | Description |
| --- | --- |
| position | Where the module will appear.  Valid values are: `top_right`, `center`, `bottom_right` or any value that is supported by MagicMirror. |
| header | The name of the header to display, or `null` to not display the module's header at all. |

```javascript
{
	module: 'MMM-NextRocketLaunch',   /* Required */
	position: 'top_right',            /* Required */
	header: 'Next Rocket Launch',     /* Optional */
},
```