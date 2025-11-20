# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the `.github` repository for the Oak OSS organization. It contains organization-wide configuration files that GitHub uses across all Oak OSS repositories:

- `profile/README.md` - Organization profile displayed on github.com/oakoss
- `CONTRIBUTING.md` - Default contributing guidelines for all Oak OSS projects
- `CODE_OF_CONDUCT.md` - Community standards and expected behavior
- `SECURITY.md` - Security vulnerability reporting guidelines
- `SUPPORT.md` - Where to get help and support resources
- `FUNDING.yml` - GitHub Sponsors configuration

## Organization Context

Oak OSS is building open source tools for modern web development, including a React component library built on [Base UI](https://base-ui.com) with an extensive theme generator.

## Standard Commands for Oak OSS Projects

Individual repositories use Bun as the package manager. Common commands across projects:

```bash
bun install          # Install dependencies
bun dev              # Run development server
bun test             # Run tests
bun run build        # Build project
bun run format       # Format code
bun run lint         # Lint code
bun run typecheck    # Type check
```

## Links

- Website: <https://oakoss.dev>
- Twitter: <https://x.com/oak_oss>
- Bluesky: <https://bsky.app/profile/oakoss.dev>
- Discussions: <https://github.com/orgs/oakoss/discussions>
