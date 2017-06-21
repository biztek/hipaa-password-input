[![Build Status](https://travis-ci.org/biztek/hipaa-password-input.svg?branch=master)](https://travis-ci.org/biztek/hipaa-password-input)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/biztek/hipaa-password-input)

_[Demo and API Docs](https://biztek.github.io/hipaa-password-input/components/hipaa-password-input/)_


##&lt;hipaa-password-input&gt;

`<hipaa-password-input>` is an input element with Material Design that allows password with HIPAA security regulation standards functionality.

# \<hipaa-password-input\>

The password will match HIPAA security regulation standards.

<hipaa-password-input> is a single-line text field with Material Design styling for entering a password.

It may include an optional label, which by default is "Password". It includes a suffix to be able to show the plain text password with a toggle icon.

<hipaa-password-input auto-validate></hipaa-password-input>
The input can be automatically validated as the user is typing by using the auto-validate and required attributes. 

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install — save biztek/hipaa-password-input
```

## Usage

Import Custom Element:

```html
<link rel="import" href="bower_components/hipaa-password-input/hipaa-password-input.html">
```

And then use it:

```html
<hipaa-password-input></hipaa-password-input>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b hipaa-password-input`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push -u origin hipaa-password-input`
5. Submit a pull request

## License

Licensed under [Apache 2.0](LICENSE).
