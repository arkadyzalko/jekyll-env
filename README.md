## Installation
```
gem install jekyll-env
```
or add it to your `Gemfile`:
```
gem 'jekyll-env'
```

## Usage

Require the gem in `plugins/ext.rb`
```
require 'jekyll-env'
```

Or require the gems in the configuration
```
gems: ['jekyll-env']
```

## Example
```html
Environment variable: {{ site.env.VARIABLE_NAME }}
```
