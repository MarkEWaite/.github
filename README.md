Global configurations for the jenkinsci GitHub organization
====

This repository stores GitHub configurations which then get applied to the project repositories.
It includes various settings for GitHub itself, GitHub applications, and other components.
See [this thread](https://groups.google.com/forum/#!topic/jenkinsci-dev/dOs8YRQwQiI) for details.

## Available Global Configurations

Currently the following features are configured globally:

* [Code of Conduct](./CODE_OF_CONDUCT.md) - Automatic referencing of Code of Conduct when creating new issues or pull requests
  ([more info](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization))
* [Issue Templates](./ISSUE_TEMPLATE/) - templates for newly created Issues and Feature Requests.
* [Pull Request Template](./pull_request_template.md) - template for pull request creation.
* [Security Links](./SECURITY.md) - Automatic referencing of Jenkins security policies when creating new issues or pull requests
  ([more info](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization))
* [Release Drafter](./.github/release-drafter.adoc) - Changelog automation

## Contacting Jenkins GitHub admins

The following channels can be used:

* Jira - Create a ticket in [Jenkins Jira](https://issues.jenkins-ci.org) (project=`INFRA`, component=`github`)
* Mailing lists - Use the [Jenkins Infrastructure mailing list](https://jenkins.io/mailing-lists/#infra-lists-jenkins-ci-org)
* IRC - Use the [#jenkins-infra](https://jenkins.io/chat/#jenkins-infra) channel on Freenode
* GitHub - Mention [@jenkinsci/github-admins](https://github.com/orgs/jenkinsci/teams/github-admins) in pull requests or GitHub issues. Available to org members only

Jenkins Jira and mailing lists are the recommended ways to send queries.

## Contributing

* To change existing configurations, just submit a pull request
* To propose a new configuration (new GitHub Apps and so on), please start a discussion in the [Jenkins developer mailing list](https://groups.google.com/d/forum/jenkinsci-dev) to get the community feedback
