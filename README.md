# Minimal, Reproducible Example for Hatch Bug

Minimal, reproducible example of a hatch bug on Windows when the [environment is
restricted to select
variables](https://hatch.pypa.io/latest/config/environment/overview/#filters),
that means you configure something like:

```toml
[tool.hatch.envs.test]
env-include = [
    "MYAPP_*",
]
```

## Unlicense

Source code is dedicated to the public domain, [see unlicense](./UNLICENSE).

