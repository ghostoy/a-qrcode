# &lt;a-qrcode&gt;

A QRCode generator based on Polymer and [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs) library

> Maintained by [Cong Liu](https://github.com/ghostoy).

## Demo

> [Check it live](http://ghostoy.github.io/a-qrcode).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20131107/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/a-qrcode.html">
	```

3. Start using it!

	```html
	<a-qrcode code="Fill your code"></a-qrcode>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`code`     | *string*                  | `""`                | The code to be displayed as QRCode
`width`    | *int* 	   				   | `128`               | Width of the QRCode
`height`   | *int*                     | `128`               | Height of the QRCode


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 Nov 29, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)