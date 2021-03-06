# Development

Local development environment can be set up via docker-compose:

```shell
docker-compose up -d
```

To run specs within the docker container:

```shell
docker-compose exec app bundle exec rake spec
```

# Pull Request Guidelines

A Pull Request will only be accepted if it addresses a specific issue that was reported previously, or fixes typos, mistakes in documentation etc.

Other requirements:

1. Do not open a pull request if you can't provide tests along with it. If you have problems writing tests, ask for help in the related issue.
2. Follow the style conventions of the surrounding code. In most cases, this is standard ruby style.
3. Add API documentation if it's a new feature
4. Update API documentation if it changes an existing feature
5. Bonus points for sending a PR to [github.com/rom-rb/rom-rb.org](https://github.com/rom-rb/rom-rb.org) which updates user documentation and guides

# Issue Guidelines

## Reporting bugs

If you found a bug, report an issue and describe what's the expected behavior versus what actually happens. If the bug causes a crash, attach a full backtrace. If possible, a reproduction script showing the problem is highly appreciated.

## Reporting feature requests

Report a feature request **only after discussing it first on [discourse.rom-rb.org](https://discourse.rom-rb.org)** where it was accepted. Please provide a concise description of the feature, don't link to a discussion thread, and instead summarize what was discussed.

## Reporting questions, support requests, ideas, concerns etc.

**PLEASE DON'T** - use [discourse.rom-rb.org](http://discourse.rom-rb.org) instead.

# Asking for help

If these guidelines aren't helpful, and you're stuck, please post a message on [discourse.rom-rb.org](https://discourse.rom-rb.org).
