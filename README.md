# Generate Daily Release Tag Action

Generates a daily incremental git tag in the format:

```
YYYY-MM-DD-N
```

Example:

```
2026-01-01-1
2026-01-01-2
```

## Usage

```yaml
- uses: GNITOAHC/daily-release-tag-action@v1
  id: tagger
```

Then access:

```yaml
${{ steps.tagger.outputs.tag }}
```
