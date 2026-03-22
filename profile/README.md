# jsondelta

> [!NOTE]
> This ecosystem is archived. The WASM serialization boundary (JSON.stringify -> memory copy -> Zig parse -> compute -> serialize -> copy -> JSON.parse) dominates computation time, making the engine slower than pure JS alternatives. The JS fallback is competitive but offers no advantage over existing libraries like fast-json-patch.

## Packages

| Package | Version | Description |
|---------|---------|-------------|
| [`@jsondelta/diff`](https://github.com/jsondelta/diff) | [![npm](https://img.shields.io/npm/v/@jsondelta/diff)](https://www.npmjs.com/package/@jsondelta/diff) | Structural JSON diffing with reversible deltas |
| [`@jsondelta/patch`](https://github.com/jsondelta/patch) | [![npm](https://img.shields.io/npm/v/@jsondelta/patch)](https://www.npmjs.com/package/@jsondelta/patch) | Patch application and delta inversion |
| [`@jsondelta/merge`](https://github.com/jsondelta/merge) | [![npm](https://img.shields.io/npm/v/@jsondelta/merge)](https://www.npmjs.com/package/@jsondelta/merge) | Three-way merge with conflict detection |
| [`@jsondelta/bench`](https://github.com/jsondelta/bench) | | Benchmark suite vs deep-diff, jsondiffpatch, fast-json-patch |

---

This ecosystem was an experiment in AI-maintained open source. All packages were autonomously built, tested, and refined by AI with human oversight.
