# PlutoBoard.jl Documentation

```@contents
```

## Interface functions

### Julia interface
```@docs
initialize(_html_path::String, _css_path::String; fullscreen::Bool = false, bootstrap::Bool = false, hide_notebook::Bool = true)
```

### JavaScript interface
These functions can be called in the browser and are written in **JavaScript**.
```@docs
callJuliaFunction()
```

## Internal functions

### Julia internal functions
```@docs
load_bootstrap_css()
load_bootstrap_js()
load_html()
load_html_string_to_body()
load_js()
```

### JavaScript internal functions
```@docs
placeIframe()
updateAllCells()
updateCell()
insertHTMLToBody()
```