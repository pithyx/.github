<p align="center">
  <img src="logo.svg" alt="Pithyx logo" width="120" height="120">
</p>

<h1 align="center">Pithyx</h1>

<p align="center">
  Your server, with a desktop.<br>
  <a href="https://pithyx.org">pithyx.org</a> · <a href="https://pithyx.org/docs/">Docs</a> · <a href="https://pithyx.org/docs/getting-started/quick-start/">Get started</a>
</p>

Pithyx is a free, self-hosted NAS and server operating system with a web desktop. It turns a computer you own into a NAS and app server: it runs on Debian 13, manages storage with ZFS, shares files over SMB, SFTP, WebDAV and FTP, and runs apps as containers, all from a desktop in the browser that works the same on a phone and on an ultrawide monitor. Everything stays on your box: no telemetry, no cloud accounts, no services the system depends on.

## The name

Pronounced /ˈpɪθɪks/, "PITH-iks".

Pandora never opened a box. She opened a pithos (πίθος), a great storage jar of ancient Greece. Erasmus of Rotterdam later mistranslated it as pyxis, a box, and the box stuck. What stayed inside was hope. Pithyx keeps what matters, on your hardware.

The stem is pithos; the ending -yx is a stylization after Greek models such as onyx and Styx.

## Status

Pithyx 1.0 is the first public release, and it is marked **beta**. We consider it stable, but it has not yet proven itself on real boxes in everyday use. Until a stable release follows, treat it as beta and keep backups of data you care about.

## Repositories

- [pithyx](https://github.com/pithyx/pithyx): the system (daemon, web desktop, installer, image and updates) and the docs.
- [apps-official](https://github.com/pithyx/apps-official) and [apps-community](https://github.com/pithyx/apps-community): the signed app catalogs the Store reads.
- [catalog-template](https://github.com/pithyx/catalog-template): a template for a catalog of your own.
- [`@pithyx/sdk`](https://www.npmjs.com/package/@pithyx/sdk), [`@pithyx/ui`](https://www.npmjs.com/package/@pithyx/ui) and [`@pithyx/cli`](https://www.npmjs.com/package/@pithyx/cli) on npm: everything you need to build an app.

The system is licensed under the GNU AGPL-3.0 with the attribution terms in its `NOTICE`, the npm packages under MIT. Pithyx was originally created by [Schecher1](https://github.com/Schecher1).
