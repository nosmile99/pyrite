The `software` and `zettelkasten` templates (built-in copies in `pyrite init`
and the `software-kb` / `zettelkasten` extension presets) now declare the
`task` type and ship a `tasks/` directory, so `pyrite task create` works in a
freshly initialised KB without `--allow-undeclared` (#860).
