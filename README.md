# Smart Real-time Facades:

## Do not loose IDE auto-completion with real-time fcades!

Real-time facades in laravel are great, but they have a problem. When you use them, you quickly fall out of ide auto-completion and you are out of confidence.
This package generates the facade file with enough doc-blocks to provide you with all the neat IDE helps. Nice?

It works exactly like the internal laravel realtime facades.

Sample Generated File:

![image](https://user-images.githubusercontent.com/6961695/153766733-7d190d3f-b0cd-44c1-8617-a34b0bc6aa64.png)


### Install:

```bash
composer require imanghafoori/smart-realtime-facades
```

### Usage:


Just prefix your class namespace path with `_Facades\` and convert the `->` to `::` then you are good to go.

In case you want to facadize `App\Services\MyKlass`, change it to `_Facades\App\Services\MyKlass`.

`(new MyKlass)->hi();` will turn into `MyKlass::hi();`

---------------------

### :raising_hand: Contributing:

If you find an issue or have a better way to do something, feel free to open an issue, or a pull request.
If you use smart-realtime-facades in your open source project, create a pull request to provide its URL as a sample application in the README.md file.


### :exclamation: Security
If you discover any security-related issues, please email `imanghafoori1@gmail.com` instead of using the issue tracker.

----------------------


### More from the author:

#### Laravel HeyMan:

:gem: It allows us to write expressive code to authorize, validate and authenticate.

- https://github.com/imanghafoori1/laravel-heyman


#### Laravel Microscope:

:gem: Find bugs before they bit.

- https://github.com/imanghafoori1/laravel-microscope


--------------------


### Credits

- [Iman](https://github.com/imanghafoori1)
- [All Contributors](../../contributors)

### License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
