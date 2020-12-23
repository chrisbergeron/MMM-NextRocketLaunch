# MMM-NextRocketLaunch
Magic Mirror Module to display the Next Rocket Launch

## Installation
````
git clone https://github.com/chrisbergeron/MMM-NextRocketLaunch.git
````

![](example1.png)


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