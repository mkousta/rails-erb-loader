# Change Log

## [3.0.0] - 2016-11-19
- **Breaking** Use `Erubis` instead of `ERB` gem to render templates. This gem is bundled by default with Rails 3.0 and above. - #7

## [2.0.0] - 2016-11-07
- **Breaking** Rename project from `uh-erb-loader` to `rails-erb-loader` - #6
- **Breaking** Add file caching by default - #4
- Add support for query parameters
 - `cacheable`
 - `dependencies`
 - `dependenciesRoot`
 - `parseComments`
- Add configuration comments
 - `rails-erb-loader-depedencies`
 - `rails-erb-loader-depedencies-root` (undocumented)
 - `rails-erb-loader-cacheable`

## [1.1.1] - 2016-11-07
Deprecate `uh-erb-loader` in favor of `rails-erb-loader`.

## [1.1.0] - 2016-05-26
- Ignore unwanted output from Rails by delimiting desired output. - #1

## [1.0.0] - 2016-05-05
Initial release
