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

To use, just add the following to the MagicMirror config file ( it's named config/config.sh ):
```

```
Then reload MagicMirror.


To customize the appearance of the module, you can override the default values by editing the css/custom.css file:


```
/* MMM-NextRocketLaunch */
    .module.MMM-NetworkScanner {
        background-color:rgba(0,0,0,0.0);  
    }
```

Configuration:

```javascript
{
	module: 'MMM-NextRocketLaunch',
	position: 'top_right',
	header: 'Next Rocket Launch',
	config: {
		url: 'https://xyz/abc/get.json', // Required
		arrayName: 'items' // Optional
	}
}
```