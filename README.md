# `present.nvim`

this is a plugin for presenting markdown files.

# Features: Neovim Lua Execution
Present can execute code in Language Blocks, when you have them in a slide.
Only one snippet per slide is currently supported.

```lua
print("Hello World", 29)
```

# Features: Other languages
You may need to configure this with `opts.executors`.
Currently only Python and Javascript are supported by default.

# Javascipt
```javascript
console.log({myField: true, other: false})
```

# Python
```python
print("hello world", 5 + 4)
```

# Usage
```lua
require("present").start_presentation({})
```

Open a README.md

use `:PresentStart` Command.

Use `n`, and `p` to navigate markdown slides.
use `q` to exit present.
Use `x` to run a code block.
Use `:q` to exit the code block execution.

