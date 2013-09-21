# &lt;facebook-button&gt;

Web Component wrapper for [Facebook's button](https://developers.facebook.com/docs/reference/plugins/like/) using Polymer.

## Demo

![Facebook Element](http://zno.io/Quih/facebook-element.png)

> [Check it live](http://zenorocha.github.io/facebook-button).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/facebook-button.html">
	```

3. Start using it!

	```xml
	<facebook-button></facebook-button>
	```

## Options

Attribute     | Options             | Default        | Description
---           | ---                 | ---            | ---
`action`      | `like`, `recommend` | `like` | The verb to display in the button
`colorscheme` | `light`, `dark` | `light` | The color scheme for the like button
`font`        | `arial`, `lucida grande`, `segoe ui`, `tahoma`, `trebuchet ms`, `verdana` | `arial` | The font to display in the button
`href`        | *string* | `http://customelements.io` | The URL to like/recommend
`layout`      | `standard`, `button_count`, `box_count` | `button_count` | Determines the size and amount of social context next to the button
`showfaces`   | `true`, `false` | `false` | Specifies whether to display profile photos below the button (standard layout only)
`height`       | *int* | `20` | The height of the button
`width`       | *int* | `120` | The width of the button

> See Facebook's [official documentation](https://developers.facebook.com/docs/reference/plugins/like/).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.2](https://github.com/zenorocha/facebook-button/releases/tag/0.1.2) September 6, 2013
	* Rename element from `<facebook>` to `<facebook-button>`
	* Rename repo from `facebook-element` to `facebook-button`
* [v0.1.1](https://github.com/zenorocha/facebook-button/releases/tag/0.1.1) September 3, 2013
	* Use Polymer from CDN and update it to v0.0.20130816
* [v0.1.0](https://github.com/zenorocha/facebook-button/releases/tag/0.1.0) August 20, 2013
	* Initial development release
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha