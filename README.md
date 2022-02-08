# Smart Realtime Facades:

Real-time facades in laravel are great, but they have a problem. When you use them, you quickly fall out of ide auto-completion and you are out of confidence.
This package generates the facade file with enough doc-blocks to provide you with all the neat IDE helps. Nice?

It works exactly like the internal laravel realtime facades.

Just prefix you class namespace path with `_Facades\` and convert the `->` to `::` then you are good to go.

### Install:

```bash
composer require imanghafoori/smart-realtime-facades
```