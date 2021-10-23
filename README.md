# mixed-content-laravel

I set ASSET_URL in the .env to the https url:

APP_URL=https://example.com
ASSET_URL="${APP_URL}"

This overrides the asset() function to use the https url, without having to modify the function at all. See the docs for more context.

DOCS link: https://laravel.com/docs/6.x/helpers#method-asset
