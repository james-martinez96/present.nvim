# `present.nvim`

this is a plugin for presenting markdown files.

# Features: Neovim Lua Execution
Can execute code in lua blocks, when you have them in a slide

```lua
print("Hello World", 29)
```

# Features: Other languages
Can execute code in Language blocks, when you have them in a slide.
You may need to configure this with `opts.executors`, only have Python and Javascript by default.

# Javascipt
```javascript
console.log({myFiled: true, other: false})
```

# Python
```python
print("hello world", 5 + 4)
```

# Usage
```lua
require("present").start_presentation({})
```

Use `n`, and `p` to navigate markdown slides.

Or use `:PresentStart` Command.

