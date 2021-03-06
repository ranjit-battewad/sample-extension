**NOTE: This is a Sencha Extension example listing provided for you to use as a guide for your own Sencha Extensions. You can use this listing as an example, or you can clone it to create your listing. You can link to your listing in your SenchaDevs profile.**

**Learn how to distribute your extension, so it’s easy to use. Read [How To Create and Distribute Your Sencha Ext JS Extension](https://github.com/sencha/sample-extension/wiki/How-To-Create-and-Distribute-Your-Sencha-Ext-JS-Extension) guide.**

# Easy Button

![Sencha Easy Button](https://github.com/sencha/sample-extension/blob/master/images/easy_button.png "Easy Button")

A simple button that shows “That was easy!” message in a pop-up dialog when user clicks on it, as shown below:

![Easy Button Click](https://github.com/sencha/sample-extension/blob/master/images/button_click_msg.png "Easy Button Click")

## Demo
You can test drive the [online demo](https://sencha.github.io/sample-extension/).

## Running Examples
You can also run the example available under the `examples` folder by following these quick steps:

1. Clone the repository	

2. `cd /path/to/folder`

3. Run the following command to install Ext JS framework:
```
sencha workspace install --frameworks ~/Downloads/ext-6.2.1
```

4. `cd examples/easy-button-classic`

5. Run `sencha app watch` and open [http://localhost:1841/examples/easy-button-classic/](http://localhost:1841/examples/easy-button-classic/) in your browser

## How to Use This Extension

To use this package:

1. Create an application by running the following command:
	```
	sencha -sdk /path/to/sdk/folder generate app AppName /path/to/app/folder
	```

2. Copy `ext-easy-button` folder to your application `packages/local` folder. You migth need to create the `local` folder if it doesn't already exist.

3. Modify `app.json` file to include `ext-easy-package` package to the `requires`, as shown below:

	```javascript
	"requires": [
			"font-awesome",
			"ext-easy-button"
		 ],
	```

4. Run `sencha app refresh`. The package is ready for use in your application. You can start referring to the button using the xtype - `easybutton` - or class `EasyButton.button.Easy`.

## Having a Problem Using the Extension?
Please create an [issue on GitHub](https://github.com/sencha/sample-extension/issues) or send an email to ajit.kumar@sencha.com.

## License
Licenses are located under [packages/local/ext-easy-button/licenses](https://github.com/sencha/sample-extension/tree/master/packages/local/ext-easy-button/licenses) folder.
