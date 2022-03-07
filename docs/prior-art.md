# Prior Art

The most popular solutions for Git hooks include

- [husky](https://github.com/typicode/husky)
- [overcommit](https://github.com/sds/overcommit)
- [pre-commit](https://github.com/pre-commit/pre-commit)

The latter two have quite a bit of code bloat; probably because they were created before `core.hooksPath` was implemented. The foremost solution has been modified to use the new `core.hooksPath` configuration setting, but I prefer something that is both written in Bash and includes a small library for hooks