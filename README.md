# Strict Precision Mode

A portable agent skill that requires verified, scope-bound, exact responses. It is compatible with the [skills CLI](https://github.com/vercel-labs/skills), which can install skills into its supported agents.

## Install

Run the following command and choose the agents, installation scope, and installation method when prompted:

```powershell
npx skills add ahmedhabibmezni/Strict-Precision-Mode --skill strict-precision-mode
```

Restart the target agent after installation.

Do not add `--agent '*'` unless the intention is to install into every supported agent. Add `-g` only when the skill should be available globally instead of in one project.

## Limits

The skill cannot control AI products that do not support Agent Skills and cannot override system, developer, safety, or other higher-priority instructions.

## Update

```powershell
npx skills update strict-precision-mode -g
```

## License

MIT. See [LICENSE](LICENSE).
