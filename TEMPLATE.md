# Template Notes

- https://nodejs.org/en/about/previous-releases
- https://docs.deno.com/runtime/manual/node
- Biome:
  - https://biomejs.dev/internals/changelog/
  - https://biomejs.dev/linter/rules/no-nodejs-modules/

## Commands

```bash
npm install ... && npm install -D @biomejs/biome sort-package-json jiti npm-run-all2
```

## Snippets

```ini
root = true

[*]
end_of_line = lf
insert_final_newline = true
trim_trailing_whitespace = true
charset = utf-8

# Source: https://biomejs.dev/guides/how-biome-works/#protected-files
# To ensure consistent indent size with Biome (package.json is ignored by Biome):
[package.json]
indent_size = 2
```
