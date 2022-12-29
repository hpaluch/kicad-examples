# Sample KiCAD projects

Here are my random sample projects for KiCAD.

Tested under OpenSUSE LEAP 15.2 with this package:

```
rpm -q kicad
kicad-5.1.8-lp152.2.3.1.x86_64
```

If your KiCad crashes on Intel i915 card, you can
try this tip from https://wiki.archlinux.org/title/intel_graphics

To run schematic editor:
```bash
MESA_LOADER_DRIVER_OVERRIDE=i965 eeschema
```

Or run whole KiCad:
```bash
MESA_LOADER_DRIVER_OVERRIDE=i965 kicad
```


## Projects

* `tz1-mvb/` - simple AF multivibrator from TZ1 kit (was
   "tranzistor tester kit 1" sold around '85 in socialism era).

