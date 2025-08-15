# General Contribution Guidelines 
Welcome to Block's open source community\! We're excited that you're interested in contributing to our projects. This guide provides general guidelines for contributing to any of Block's open source repositories. Projects may have more specific guidelines than those presented here; in those cases, you may follow the direction set forth by the project maintainers either adding to these or superseding these guidelines as advised by the project maintainers.

## **Getting Started**

Whether you're fixing a typo, improving documentation, or adding a new feature, every contribution matters. This section will guide you through the basic steps to get started with contributing to Block's open source projects.

1. **Fork the Repository**  
   * Great instructions for cloning to your personal fork and using that for branches are provided by GitHub [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).   
2. **Create a Branch**  
   * Create a branch for your work: git checkout \-b feature/your-feature-name  
   * Use descriptive branch names that reflect the changes you're making  
3. **Set Up Development Environment**  
   * Follow the project-specific setup instructions in the repository's README.md  
   * Ensure you have all necessary dependencies installed  
   * Run any required initialization scripts

## **Making Changes**

1. **Discuss Your Plans:** Join our [Discord community](https://discord.gg/block-opensource) or use the Issue Tracker to discuss your proposed changes with project maintainers. This helps:  
   * Ensure your plans align with the project's direction  
   * Get early feedback on your approach  
   * Avoid duplicate efforts  
   * Identify potential challenges early  
   * Connect with other contributors interested in similar work  
   * **For Substantial Changes:**  
     1. Open an issue describing your proposed changes before starting work  
     2. Wait for maintainer feedback and discussion  
     3. Get alignment on the implementation approach  
     4. Break down large changes into smaller, manageable pull requests  
2. **Write Good Code**  
   * Follow the project's coding style and conventions  
   * Write clear, self-documenting code  
   * Include comments where necessary  
   * Keep functions and methods focused and concise  
   * Write or update tests as needed  
3. **Commit Guidelines**  
   * Make focused, atomic commits that address a single concern  
   * Write clear commit messages with a descriptive title and detailed body  
   * Follow the conventional commits format: type(scope): description  
   * Common types include: feat, fix, docs, style, refactor, test, chore from the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) guidelines  
   * Example commit message:

```
feat(auth): add OAuth2 support for social login

- Implement OAuth2 authentication flow
- Add configuration options for multiple providers
- Update documentation with setup instructions
```

4. **Documentation**  
   * Update relevant documentation to reflect your changes  
   * Include inline code documentation where appropriate  
   * Update README.md if necessary  
   * Add comments explaining complex logic

## **Submitting Changes**

1. **Before Submitting**  
   * Run all tests and ensure they pass  
   * Check code formatting and linting  
   * Review your changes for clarity and completeness  
   * Rebase your branch on the latest upstream main/master  
2. **Creating a Pull Request**  
   * Push your changes to your fork  
   * Create a pull request from your branch to the main repository  
   * Fill out the pull request template if provided  
   * Link to any related issues  
   * Provide a clear description of your changes  
   * To accept your pull request, we may need you to submit CLA/DCO. If you have signed the CLA for another Block project, you can skip this. You only need to do it once.  If you are submitting a pull request for the first time, just let us know that you have completed the CLA and we can cross-check with your GitHub username.
     * Projects using the Apache license must have a [Developer Certificate of Origin](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin) sign-off on   all commits. This is a statement indicating that you are allowed to make the contribution and that the project has the right to distribute it under its license. When you are ready to commit, use the `--signoff` flag to attach the sign-off to your commit: `git commit --signoff ...`
3. **Pull Request Guidelines**  
   * Keep PRs focused and reasonable in size \- generally as small as possible to fulfill one atomic feature, task, or bug fix  
   * Include screenshots or examples for UI changes  
   * List any breaking changes  
   * Update tests and documentation  
   * Respond to review feedback promptly

## **Review Process**

1. **Code Review**  
   * All submissions require review  
   * Be open to feedback and suggestions  
   * Address review comments thoroughly  
   * Ask questions if something isn't clear  
2. **Continuous Integration**  
   * Ensure all CI checks pass  
   * Fix any failing tests or lint issues  
   * Update your PR if needed

## **Getting Help**

* Check the project's documentation first  
* Search existing issues and discussions  
* Ask questions in the project's discussions or issue tracker  
* Be clear and specific when asking for help  
* Share solutions that might help others

## **Best Practices**

1. **Communication**  
   * Be respectful and professional in all interactions  
   * Provide context when discussing issues or changes  
   * Keep discussions focused and constructive  
   * Use clear and concise language  
2. **Project Maintenance**  
   * Stay engaged with your contributions  
   * Help review other contributors' work  
   * Report bugs when you find them  
   * Suggest improvements constructively  
3. **Security**  
   * Never commit sensitive information  
   * Report security vulnerabilities [privately](https://github.com/block/.github/blob/main/SECURITY.md)  
   * Follow security best practices  
   * Use dependencies with no known security vulnerabilities

## **Recognition and Other Ways to Contribute**

There are numerous ways to be an open source contributor to Block projects. We're here to help you on your way\! Here are some suggestions to get started:

* **Stars on GitHub:** If you find our projects valuable, consider starring them on GitHub\! 🌟  
* **Ask Questions:** Your questions not only help us improve but also benefit the community. Don't hesitate to ask questions in project discussions.  
* **Give Feedback:** Have a feature you want to see or encounter an issue? Open an issue in the relevant repository or start a discussion.  
* **Participate in Community Events:** We host various community events and livestreams. Follow Block's open source channels to stay informed about upcoming events.  
* **Improve Documentation:** Good documentation is key to the success of any project. You can help improve the quality of existing docs or add new pages.  
* **Help Other Members:** See another community member stuck? Or a contributor blocked by a question you know the answer to? Reply to community threads or do a code review.  
* **Showcase Your Work:** Working on something interesting with our projects? Share it with the community\!  
* **Give Shoutouts:** Recognize helpful community members or maintainers who've made a difference.  
* **Spread the Word:** Help us reach more people by sharing Block's open source projects and initiatives.

We value all contributions, whether they're:

* Code changes  
* Documentation improvements  
* Bug reports  
* Feature suggestions  
* Code reviews  
* Answering questions

Every single contribution matters, and we're thrilled you're here to learn and contribute with us. If you feel like you’re stuck, reach out to project maintainers for help.

## **License**

By contributing to Block projects, you agree that your contributions will be licensed under the project's license. Make sure you understand and agree to the license terms before contributing.

## **Code of Conduct** 
By participating in our community, you agree to abide by our [Code of Conduct](https://github.com/block/.github/blob/main/CODE_OF_CONDUCT.md). We are committed to providing a welcoming and inclusive environment for all contributors, regardless of background or experience level. The Code of Conduct is maintained by and upheld by the [Block Open Source Governance Committee](https://github.com/block/.github/blob/main/GOVERNANCE.md). 

## **Questions?**

If you have questions about contributing that aren't covered here, please:

1. Check the project-specific documentation  
2. Open a discussion in the repository  
3. Reach out to the project maintainers

Thank you for contributing to Block's open source projects\! 
