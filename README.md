# Svelte v5 VSCode No app.html reproduction

The `main` branch features the bug setup with just `npx sv create`, `npm install --save-dev sass`, and creating two npm workspaces. Each `vite.config.ts` is extended from the root. There is a `v4` branch that does not feature the bug where the only difference is the installed versions of `@sveltejs/vite-plugin-svelte`, `svelte`, and `vite`. There is also a `no-extended-vite-config` branch featuring a workaround where the `vite.config.ts` is duplicated rather than extended.
