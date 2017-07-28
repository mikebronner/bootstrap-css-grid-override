# bootstrap-css-grid-override
Update bootstrap 4 with native CSS-grid with graceful degradation.

## Supported Classes
- `row`
- `col-*-*`
- `offset-*-*`

## Example
Include it in your master SCSS **after** you include bootstrap:
```scss
@import "node_modules/bootstrap/scss/bootstrap";
@import "grid";
```
Then build with WebPack or Grunt as usual.

Please submit PRs to improve the functionality.
