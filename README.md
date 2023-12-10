# Module: MMM-Pure-Snow

Inspired by [hyperstown's pure-snow.js](https://github.com/hyperstown/pure-snow.js/blob/master/pure-snow.js) I created a wrapper plugin to improve your winter experience!

**Screenshot**

![](.github/example-water.png)

## Installation

In your terminal, go to your MagicMirror's Module folder:

```
cd ~/MagicMirror/modules
```

Clone this repository:

```
git clone https://github.com/ptornhult/MMM-Pure-Snow.git
```

Configure the module in your `config.js` file.

## Using the module

To use this module, add it to the modules array in the `config/config.js` file:

```javascript
modules: [
  {
    module: "MMM-Pure-Snow",
    position: "fullscreen_below",
	  config: [
		  dataCount: "200"
	  ]
  },
];
```