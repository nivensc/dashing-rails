## 2.0.0

* Refactor assets management. Now they all live in `vendor` directory.
* Introduce a widget generator to build custom widget in a few seconds (`rails g dashing:widget my_widget`).
* Rename configuration attributes (you need to regenerate the initializer config file with `rails g dashing:install`)
* Simplify widget view path
* Bug fixes

## 1.0.3

* cherrypick https://github.com/Shopify/dashing/pull/253
* cherrypick https://github.com/Shopify/dashing/commit/2b715ac63dd2de5c718142822663dbded44bbecd
* cherrypick https://github.com/Shopify/dashing/commit/9f93895bd40aad02e88f7ed7bfd954c930aa27db
* cherrypick https://github.com/Shopify/dashing/commit/9496b31d7787182b561bd99f8674901bd7667976
* cherrypick https://github.com/Shopify/dashing/pull/181
* cherrypick https://github.com/Shopify/dashing/commit/3af326da84251069c4e6f7464d0ae8506b20e98b
* cherrypick https://github.com/Shopify/dashing/pull/211

## 1.0.2

* Fix redis connection. Now using connection pool
* Allow redis custom connection using custom redis host, port and password.