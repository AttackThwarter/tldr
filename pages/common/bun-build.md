# bun build

> Bundle JavaScript, TypeScript, JSX, and more.
> More information: <https://bun.sh/docs/bundler>.

- Build a single entrypoint file into an output directory:

`bun build {{path/to/entry}} --outdir {{path/to/outdir}}`

- Build multiple entrypoints into an output directory:

`bun build {{path/to/entry1 path/to/entry2 ...}} --outdir {{path/to/outdir}}`

- Build and minify the output for production:

`bun build {{path/to/entry}} --outdir {{path/to/outdir}} --minify`

- Build for a specific runtime (browser, node, or bun):

`bun build {{path/to/entry}} --outdir {{path/to/outdir}} --target {{browser|node|bun}}`

- Rebuild automatically when files change (watch mode):

`bun build {{path/to/entry}} --outdir {{path/to/outdir}} --watch`

- Exclude a package from the bundle (mark as external):

`bun build {{path/to/entry}} --outdir {{path/to/outdir}} --external {{package_name}}`

- Compile an entrypoint into a single standalone executable:

