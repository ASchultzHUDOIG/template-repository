<!--

GitHub Docs: https://docs.github.com/en

A file that answer the What, Why and How of the project.
GitHub will recognize and automatically surface the README to repository visitors.

https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes
https://www.makeareadme.com/

 -->

# CIGIE Shared Services on GitHub Template Repository

A repository template for generating new projects on the CIGIE Shared Services on GitHub platform.

## Important

**After going through the information outlined in this README file please replace it with your project's content.**

## Template Structure

Most of the template files are stored under the `.github` directory. The template repository includes:

- [`ISSUE_TEMPLATE`](https://github.com/cigie-shared-services/template-repository/tree/main/.github/ISSUE_TEMPLATE)
- [`PULL_REQUEST_TEMPLATE`](https://github.com/cigie-shared-services/template-repository/tree/main/.github/PULL_REQUEST_TEMPLATE)
- [`workflows`](https://github.com/cigie-shared-services/template-repository/tree/main/.github/workflows)
- [`ACKNOWLEDGEMENTS.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/ACKNOWLEDGEMENTS.md)
- [`AUTHORS.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/AUTHORS.md)
- [`CHANGELOG.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/CHANGELOG.md)
- [`CODE_OF_CONDUCT.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/CODE_OF_CONDUCT.md)
- [`CODEOWNERS`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/CODEOWNERS)
- [`CONTRIBUTING.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/CONTRIBUTING.md)
- [`LICENSE`](https://github.com/cigie-shared-services/template-repository/blob/main/LICENSE)
- [`README.md`](https://github.com/cigie-shared-services/template-repository/blob/main/README.md)
- [`SECURITY.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/SECURITY.md)
- [`STYLE_GUIDE.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/STYLE_GUIDE.md)
- [`SUPPORT.md`](https://github.com/cigie-shared-services/template-repository/blob/main/.github/SUPPORT.md)
- [`.gitignore`](https://github.com/cigie-shared-services/template-repository/blob/main/.gitignore)

These files should be included in every project. It is up to the project owner(s) to determine
the content and the level of detail that each of these files include. Each Markdown (`.md`) file
provided by this repository contains resources that are visibile when the `Raw` button is selected
for a given file but hidden when displayed on the webpage.

## Recommendations

After a project is generated with this template the following activities are recommended but may not always apply:

1. Review GitHub and the government [best practices](https://cigie-shared-services.github.io/start-here/getting_started/github-and-the-government/) described on this page.
2. Configure [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches).
3. Configure [CODEOWNERS](https://docs.github.com/en/enterprise-cloud@latest/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) to ensure that changes to the codebase are reviewed by the owners of changed files.
4. Configure root `.gitignore` file to [ignore files](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files) that shouldn't be checked in to the repository.
   1. Ensure that any datasets, IDE configuration files, etc. are ignored. **DO NOT** push anything protected/sensitive to repositories.
5. Configure [issue templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository).
6. Configure a [pull request template](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository).
7. Setup [secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets) (if applicable).
8. Implement a branch-based workflow such as [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) for successful project collaboration.
9. Host documentation using the repository's [wiki](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis).
10. Use [discussions](https://docs.github.com/en/discussions/collaborating-with-your-community-using-discussions/about-discussions) to create and participate in conversations within the project's repository.

## License

This project is in the worldwide [public domain](LICENSE).

This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
