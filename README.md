# nitaking/skills

## Install

### Claude Code plugin

```
/plugin install <skill-name> --marketplace nitaking/skills
```

e.g.

```
/plugin install review-point-pr --marketplace nitaking/skills
/plugin install nitaking-blog-style --marketplace nitaking/skills
```

On older Claude Code versions:

```
/plugin marketplace add nitaking/skills
/plugin install review-point-pr@nitaking-skills
```

### apm

Install an individual skill (global / user scope):

```sh
apm install -g nitaking/skills/<skill-name>
```

Or add to a project's `apm.yml`:

```yaml
dependencies:
  apm:
    - nitaking/skills/<skill-name>
```

Pin to a tag:

```sh
apm install -g nitaking/skills/<skill-name>#v0.1.0
```

## Skills

### Tooling / Infra

| Skill | Description |
| --- | --- |
| [nitaking-blog-style](nitaking-blog-style/) | Evaluation and feedback on nitaking's writing style and AI-generated writing style |

### Development workflow

| Skill | Description |
| --- | --- |
| [review-point-pr](review-point-pr/) | Create a "Review point" PR for a PR under review: lists your suggestion commits as a `commit \| finding \| change` table, based on the reviewed PR's branch |

## License

MIT
