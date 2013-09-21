# &lt;gplus-button&gt;

Web Component wrapper for [Google's +1 button](https://developers.google.com/+/web/+1button/) using Polymer.

## Demo

![GPlus Element](http://zno.io/Qvag/gplus-element.png)

> [Check it live](http://zenorocha.github.io/gplus-button).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/gplus-button.html">
	```

3. Start using it!

	```xml
	<gplus-button></gplus-button>
	```

## Options

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`type`       | `g-plusone`, `g-follow`               | `g-plusone`               | The type of button
`lang`    | `pt-BR`, `en-US`, `es`, [more languages](https://developers.google.com/+/web/+1button/#available-languages)              | `en-US`                            | language of component


## Options - button gplus

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`href`       | *string*                              | `http://customelement.io` | The URL to +1
`size`       | `small`, `medium`, `standard`, `tall` | `standard`          		 | Sets the +1 button size to render
`width`      | *int*                                 | `300`               		 | The width of the button
`annotation`  | `bubble`,`inline`,`none`             | `bubble`                  | Sets the annotation to display next to the button.


## Options - button follow

Attribute    | Options                               | Default             		 | Description
---          | ---                                   | ---                 		 | ---
`pageId`      | `URL to the Google+ page or user profile, examples: https://plus.google.com/110967630299632321627, https://plus.google.com/+LarryPage`  | `109325404047497404656`            | URL to the Google+ page or user profile
`annotation`  | `bubble`,`vertical-bubble`,`none`   | `bubble`                           | Sets the annotation to display next to the button.
`rel`         | `author or publisher`               | `string empty`                     | Describes the relationship of the entity defined at the href location to the page the badge is embedded.
`height`      | `15`,`20`,`24`                      | `20`                               | The pixel height of the button to render.


> See Google Plus' [official documentation](https://developers.google.com/+/web/+1button/).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.3](https://github.com/zenorocha/gplus-button/releases/tag/0.1.3) September 18, 2013
	* Add follow button.
* [v0.1.2](https://github.com/zenorocha/gplus-button/releases/tag/0.1.2) September 6, 2013
	* Rename element from `<gplus>` to `<gplus-button>`
	* Rename repo from `gplus-element` to `gplus-button`
* [v0.1.1](https://github.com/zenorocha/gplus-button/releases/tag/0.1.1) September 3, 2013
	* Use Polymer from CDN and update it to v0.0.20130816
* [v0.1.0](https://github.com/zenorocha/gplus-button/releases/tag/0.1.0) August 20, 2013
	* Initial development release
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha