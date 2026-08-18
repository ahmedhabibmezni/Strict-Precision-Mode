# Strict Precision Mode

A portable agent skill that requires verified, scope-bound, exact responses. It is compatible with the [skills CLI](https://github.com/vercel-labs/skills), which can install skills into its supported agents.

## Install globally

After creating the public GitHub repository, replace `<YOUR_GITHUB_OWNER>` and run:

```powershell
npx skills add <YOUR_GITHUB_OWNER>/strict-precision-mode -g --agent '*'
```

Restart the target agent after installation.

## Limits

The skill cannot control AI products that do not support Agent Skills and cannot override system, developer, safety, or other higher-priority instructions.

## Update

```powershell
npx skills update strict-precision-mode -g
```

## License

MIT. See [LICENSE](LICENSE).
