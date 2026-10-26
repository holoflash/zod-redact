# Changelog

## 1.1.0

- Support intersections (`z.intersection()` / `.and()`). Intersections of objects are seeded like the equivalent merged object, so picks stay consistent.
- Narrow `zod` peer range to `^3.25.0 || ^4.0.0`.
- Enable `isolatedDeclarations` so declarations build with TypeScript 7.
- Update dev dependencies.

## 1.0.5

- Correct repository and homepage links in `package.json`.

## 1.0.4

- Replace deprecated tsdown `external` option with `deps.neverBundle`.

## 1.0.3

- Add bundlejs badge to README.

## 1.0.2

- Ship CJS source map (`dist/index.cjs.map`) alongside ESM source map.
- Add CHANGELOG.
- Add package manager specification to `package.json`.

## 1.0.1

- Updated README.

## 1.0.0

- Initial release.
- `redact()` — annotate schema fields with static, array, or function replacements.
- `parseAndRedact()` / `safeParseAndRedact()` — parse-then-redact in one step.
- `parseAndRedactAsync()` / `safeParseAndRedactAsync()` — async variants.
- `applyRedact()` — redact already-parsed data.
- `combine()` — derived multi-field redaction from component arrays.
- DJB2-based deterministic seeding with automatic `id` field resolution.
- Supports objects, arrays, records, tuples, maps, sets, unions, pipes, optionals, nullables, defaults, readonly, catch, lazy, and nested combinations.
