<p align="center">
  <a href="https://github.com/Vumlo/vumlo-core">
    <img src="https://raw.githubusercontent.com/Vumlo/vumlo-core/main/brand/vumlo-logo.png" alt="Vumlo" width="320">
  </a>
</p>

<p align="center">
  <b>A self-hosted learning platform for one school or university.</b><br>
  Courses, assignments, grading and a gradebook, on your own server, with your data staying there.
</p>

<p align="center">
  <a href="https://vumlo-demo.partum55.me">Live demo</a> ·
  <a href="https://vumlo.partum55.me">Website</a> ·
  <a href="https://github.com/Vumlo/vumlo-core/releases/latest">Latest release</a> ·
  <a href="https://github.com/Vumlo/vumlo-core/blob/main/docs/install.md">Install guide</a>
</p>

## Get started

```sh
npx create-vumlo
```

The installer downloads the newest release, verifies its checksum, asks a few questions about your institution and writes
the configuration. [Try the demo](https://vumlo-demo.partum55.me) first: pick a student, a teacher or an administrator of a
made-up university, no sign-up needed.

## What Vumlo is

- **Teachers** build courses from sections, give text, file, quiz and form assignments, grade next to the student's work
  and publish grades when ready.
- **Students** write with saved drafts, take quizzes, see deadlines and read grades only once they are published.
- **Administrators** manage people, terms, groups and an audit log. Sign-in by password or Google.
- **A desktop app** for Windows, macOS and Linux, built from your own configuration, works offline.
- **Plugins in any language** extend it without a fork: an HTTP service that Vumlo does not trust, told about events and
  limited to the scopes you grant.

Written in Rust. MIT licensed.

## Repositories

| Repository | What it is |
|---|---|
| [**vumlo-core**](https://github.com/Vumlo/vumlo-core) | The platform: backend, web app, desktop app, deploy scripts and documentation |
| [**create-vumlo**](https://github.com/Vumlo/create-vumlo) | The installer: `npx create-vumlo` |
| [**vumlo-plugins**](https://github.com/Vumlo/vumlo-plugins) | A Python SDK and ready-made plugins: at-risk students, grade anomalies, deadline alerts and more |

## Contribute

Found a bug or have an idea? Open an issue in the matching repository. To build a plugin, start with the
[plugin SDK guide](https://github.com/Vumlo/vumlo-plugins/blob/main/vumlo_plugins/README.md) and the
[hello-plugin example](https://github.com/Vumlo/vumlo-core/tree/main/examples/hello-plugin).
