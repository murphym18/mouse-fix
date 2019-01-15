# Mouse-fix

I use xinput and I wrote a script to change the mouse cursor speed.

# Install

Copy the file called `mouse-fix` to `$HOME/bin` or some other directory on the `$PATH`.

# Usage

First run:

```bash
xinput
```

Look at the output and find the device ID associated with your mouse. For example, the output might say:

```
Logitech MX Master 2S                   	id=9	[slave  pointer  (2)]
```

This output indicates the mouse has device ID 9.

Run mouse-fix with the device ID:

```bash
mouse-fix 9
```

Optionally run mouse-fix with the device ID and a custom pointer speed argument:

```bash
mouse-fix 9 '-0.7'
```

That's it.
