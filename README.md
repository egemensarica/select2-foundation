# Select2-Foundation

select2 (v4) Theme for Zurb Foundation (v6)

[Examples](https://select2-foundation.herokuapp.com/ "select2-foundation examples")

## Installation

### Manual Install

In order to apply select2-foundation theme to your project, add the following files:

    <link rel="stylesheet" href="select2.css">
    <link rel="stylesheet" href="select2-foundation-theme.css">

### Bower

  "dependencies": {
    "foundation-sites" : "latest",
    "select2" : "latest",
    "select2-foundation" : "https://github.com/egemensarica/select2-foundation.git#v6"
  }

### Apply the theme

Configure select2 To apply the theme by passing `foundation` to the theme option when initializing:

    $( "#dropdown" ).select2({
        theme: "foundation"
    });


## Development

### Building `dist`

Install build tools:

* npm
* grunt-cli

Run grunt tasks. See grunt help for available tasks.

      grunt sass

## Changelog

### 0.0.1
 * Initial sass

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
