# &lt;gravatar&gt;

Web Component wrapper for Gravatar using Polymer

> Maintained by [Djalma Araújo](https://github.com/djalmaaraujo).

## Demo

> [Check it live](http://djalmaaraujo.github.io/gravatar-element).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/gravatar.html">
	```

3. Start using it!

	```html
	<gravatar username="your-gravatar-email-here"></gravatar>
	```

## Options

Attribute   | Options                   | Default                 | Description
---         | ---                       | ---                     | ---
`username`  | *string*                  | `someemail@example.com` | Your gravatar email
`size`      | *int* 	                  | `80`               		  | The img size
`customurl` | *string*                  | `false`                 | If you want to link gravatar to a custom URL


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 20, 2013
	* Created gravata element with username, size and customurl options

## License

[MIT License](http://opensource.org/licenses/MIT)