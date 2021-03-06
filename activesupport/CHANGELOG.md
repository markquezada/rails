*   Add support for versioned cache entries. This enables the cache stores to recycle cache keys, greatly saving
    on storage in cases with frequent churn. Works together with the separation of #cache_key and #cache_version
    in Active Record and its use in Action Pack's fragment caching.

    *DHH*

*   Pass gem name and deprecation horizon to deprecation notifications.

    *Willem van Bergen*

*   Add support for `:offset` and `:zone` to `ActiveSupport::TimeWithZone#change`

    *Andrew White*

*   Add support for `:offset` to `Time#change`

    Fixes #28723.

    *Andrew White*

*   Add `fetch_values` for `HashWithIndifferentAccess`

    The method was originally added to `Hash` in Ruby 2.3.0.

    *Josh Pencheon*


Please check [5-1-stable](https://github.com/rails/rails/blob/5-1-stable/activesupport/CHANGELOG.md) for previous changes.
