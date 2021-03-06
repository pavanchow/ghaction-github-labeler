# Changelog

## 3.1.0 (2020/09/28)

* Don't use `:warning:` for everything being up-to-date (#112)
* Don't fail when "from_name" cannot be found (#111)
* Update deps

## 3.0.0 (2020/08/21)

* Move `GITHUB_TOKEN` env var to `github-token` input
* Rename `yaml_file` input to `yaml-file`
* Rename `skip_delete` input to `skip-delete`
* Rename `dry_run` input to `dry-run`
* Refactor and add tests

## 2.1.1 (2020/08/21)

* Add deprecation message since v3

## 2.1.0 (2020/07/22)

* Handle [@actions/github](https://github.com/actions/toolkit/tree/main/packages/github) v4
* Update deps

## 2.0.2 (2020/05/10)

* Cleanup local paths from extra fields
* Update deps

## 2.0.1 (2020/05/03)

* Fix exclusions
* Update deps

## 2.0.0 (2020/05/01)

* Use newline-delimited list for exclusions
* Add missing exclude input in action.yml
* Update deps

## 1.3.0 (2020/04/26)

* Mark workflow as failed in case of errors (#78)
* Enhanced annotations messages (#78)
* Update deps

## 1.2.0 (2020/04/09)

* Retrieve all labels through pagination (#71)
* Use ncc and clean workflows
* Update deps

## 1.1.1 (2019/11/14)

* Update deps

## 1.1.0 (2019/10/20)

* Add `exclude` option for simple wildcard matching on label names (#1)

## 1.0.0 (2019/10/18)

* Initial version
