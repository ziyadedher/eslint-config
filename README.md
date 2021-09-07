# eslint-config-ziyad

🛠🚀 Ziyad's ESLint configuration for hypermodern web development (TypeScript + Next.js + TailwindCSS).

This is part of a larger effort to streamline the process of very quickly spinning up high-quality webapp projects (mostly for myself). A link to more information will eventually land here.

## Philosophy

I really like [Black](https://github.com/psf/black)'s concept of an uncompromising Python code formatter. There are three major tenants of the philosophy this configuration follows:

1. Eliminate the need to think about the minutiae of code style.
1. Provide a universal, easy-to-follow style guide for new projects.
1. Encourage the use of well-build modern technologies.

## Rules

Check out the [.eslintrc.yaml](.eslintrc.yaml) for the most up-to-date view of what rules and plugins are enabled.

Notably, this config _does not_ introduce any new rules. It just configures existing ones.

## Versioning

This projects follows a modified [semantic versioning](https://semver.org/) scheme for major, minor, and patch releases.

- Major: a technology change (addition or removal), or otherwise completely backwards-incompatible change.
- Minor: a rule or dependency change that may be backwards-incompatible _and_ does not have an automated fix.
- Patch: a rule or dependency change that is either backwards-compatible _or_ has an automated fix.
