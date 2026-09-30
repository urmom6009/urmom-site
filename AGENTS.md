# project instructions

## scope and architecture

Existing Astro + Cloudflare lab site. src/pages holds routes; public holds static assets. Keep this distinct from the professional colinvargas.com repository. Do not migrate deployment providers or expose homelab administrative controls.

## setup and validation

Install: `bash .codex/setup.sh`. Validate: `bash .codex/validate.sh`. Read `.codex/README.md` for environment publication and startup instructions. These commands do not activate a cloud environment automatically.

package.json requires Node >=22.12.0; use a runtime compatible with its current Astro dependency. If package-lock.json exists, use npm ci; otherwise npm install and review dependency changes. Run npm run build. npm run dev serves the Astro development environment. npm run preview builds and invokes wrangler dev; treat it as a local Cloudflare-emulation check that may need additional runtime configuration.

Do not run npm run deploy during cloud environment setup or validation: it invokes wrangler deploy. Keep Cloudflare account credentials and live bindings out of cloud development. Use synthetic fixtures for any private systems data.

## privacy boundary

This repository is eligible for GitHub + cloud Codex development only for its existing noncommercial scope. Do not import commercial or proprietary implementations, unpublished thesis/research, customer data, production logs, credentials, or material from other repositories. If a task introduces potentially commercial or proprietary work, stop cloud work on that material and keep its source and execution on the owner's local/self-hosted system. A private GitHub repository is still cloud storage. Never change repository visibility or publish/deploy as part of a development task without that task authorizing it.

## working process

Read repository and nested AGENTS.md instructions before edits. Use a dedicated branch and a pull request. Keep existing deployment targets and git history. Do not combine legacy repositories or infer that a similarly named repository is obsolete. Keep secrets in the appropriate runtime secret store; examples must contain placeholders. Report checks actually run and any environment limitations. Do not fabricate validation.
