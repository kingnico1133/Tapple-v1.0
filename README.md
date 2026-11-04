# Tapple

Tapple is an independent, community-hosted fallback copy of the Snap! visual programming editor. The original idea was to give people another place to open a compatible editor if the main Snap! website or its hosting has an outage. Tapple is not a replacement for Snap!, and it is not affiliated with or endorsed by the Snap! team or UC Berkeley.

## How it works

- GitHub Actions downloads the pinned official Snap! release (v12.3.10) and assembles a complete static site.
- The build checks that the editor's startup page and core JavaScript files are present before deployment.
- GitHub Pages hosts that built copy independently of snap.berkeley.edu.
- Open `snap.html` to use the editor. Use local file export/import for projects; Snap! cloud accounts and cloud saving are not provided by this independent copy.

## Run locally

Download the official [Snap! v12.3.10 source archive](https://github.com/jmoenig/Snap/archive/refs/tags/v12.3.10.zip), extract it, and open `snap.html` in a modern browser. For the most reliable local setup, follow the upstream [offline instructions](https://github.com/jmoenig/Snap/blob/master/docs/Offline.md).

## Credits and license

Tapple currently hosts the unmodified Snap! editor source from [jmoenig/Snap](https://github.com/jmoenig/Snap). Snap! was created by Jens Mönig and Brian Harvey. The source is licensed under the GNU Affero General Public License, version 3 or later (AGPL-3.0-or-later); see [LICENSE](LICENSE). The deployed site includes the corresponding source code and license notices.

Tapple is an independent fallback project, not an official Snap! service.
