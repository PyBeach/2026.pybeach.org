# 2026.pybeach.org

This is the source for [2026.pybeach.org](https://2026.pybeach.org "PyBeach 2026").

The site is built using [corvid](https://github.com/di/corvid "di/corvid: An opinionated simple static site generator") and the project is managed by [uv](https://github.com/astral-sh/uv "astral-sh/uv: An extremely fast Python package and project manager, written in Rust."). [modd](https://github.com/cortesi/modd "cortesi/modd: A flexible developer tool that runs processes and responds to filesystem changes") and [devd](https://github.com/cortesi/devd "cortesi/devd: A local webserver for developers") are highly useful for local development, but not required.


## Setup and Development

1. [Install uv](https://docs.astral.sh/uv/getting-started/installation/ "Installation | uv") to get started.
2. Run `uv sync` to set up the project locally
3. [Install modd](https://github.com/cortesi/modd?tab=readme-ov-file#install "cortesi/modd: A flexible developer tool that runs processes and responds to filesystem changes") if you’d like.
4. [Install devd](https://github.com/cortesi/devd?tab=readme-ov-file#install "cortesi/devd: A local webserver for developers") if you’d like.

Once that’s all done, the following commands are useful:

- If you installed modd and devd, run `modd` to start the build + serve daemon. You should be able to see a continuously updated local version of the site at [http://localhost:8000/](http://localhost:8000/).
- If you don’t want to use modd and devd, you can run `uv run corvid` to build the site, and then see the results in the `output/` directory.
- You can add new dependencies via `uv add`.


## Files

Files in the `input/` directory power the content of the site. corvid converts every Markdown file (`.md`) into an HTML file (`.html`), so `input/helloworld/index.md` becomes `output/helloworld/index.html`, which in turn makes it visible at `https://2026.pybeach.org/helloworld`. All other files are simply copied over.

The main template is in the `templates/` directory, should you need to edit that.
