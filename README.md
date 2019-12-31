### GitHub Actions Learning Lab Workshops Guide:

GitHub Actions is an advanced feature of GitHub that enables automation, artifact management and CI/CD natively. This workshop aims to educate you on how to implement these workflows across your projects on GitHub. We encourage you not to skip `Phase 1` as this is the most important step to implementing actions and workflows that conform to modern best practices. 

Your moderator will likely be vastly out numbered during your workshop - therefore please rely heavily on the documentation provided and available on [help.github.com](https://help.github.com/en). When you are complete, feel free to ask for feedback from your moderator and remember the best way to learn is to teach!

**Phase 1: IMPORTANT Read the Docs**
  > **The goal of Phase 1 is to understand the major concepts that will be leveraged throughout the workshop. Documentation should be read carefully and referred to often.**
  1. [Understanding Actions](https://help.github.com/en/github/automating-your-workflow-with-github-actions/about-github-actions#core-concepts-for-github-actions).
  1. [Creating a workflow](https://help.github.com/en/github/automating-your-workflow-with-github-actions/configuring-a-workflow).
  1. Integrating a 3rd party service with the [repository dispatch event](https://developer.github.com/v3/repos/#create-a-repository-dispatch-event).
  1. GitHub API - [Creating an Issue](https://developer.github.com/v3/issues/).
  1. [How to use Postman](https://learning.getpostman.com/getting-started/) to send an API request.
  ![Postman](/images/postman.png)

**Phase 2: Create your first action**
  > **The goal of Phase 2 is to Create a simple GitHub Action and use it in a workflow.**
  1. Go to the `hello world` [actions module](https://lab.github.com/github/hello-github-actions!)
  1. In this phase, you’ll learn how to:

- Organize and identify workflow files
- Add executable scripts
- Create workflow and action blocks
- Trigger workflows
- Discover workflow logs

**Phase 3: Continuous Integration with Actions**
  > **The goal of Phase 3 is to Learn how to create workflows that enable you to use Continuous Integration (CI) for your projects.**
  1. Go to the `Continuous Integration` [actions module](https://lab.github.com/githubtraining/github-actions:-continuous-integration)
  1. In this phase, you’ll learn how to:

- Describe CI and why it is necessary
- Use and customize a templated workflow
- Create CI workflows that match the team's needs and behaviors
- Use the repository's source code and build artifacts (like compiled source code) across jobs in a workflow
- Implement a unit testing framework using GitHub Actions
- Create a workflow that runs tests and produces test reports
- Set up a matrix build to create build artifacts for multiple target platforms
- Save a repository's build artifacts
- Access saved build artifacts
- Choose virtual environments for the application's CI needs

**Phase 4: Publish your Artifact to GitHub Packages**
  > **The goal of Phase 4 is to walk you through using GitHub Actions to get your code in a deployable state once your CI workflows have completed.**
  1. Go to the `Artifact Publishing` [actions module](https://lab.github.com/githubtraining/github-actions:-publish-to-github-packages)
  1. In this phase, you’ll learn how to:

- Describe CD and why it is necessary
- Use and customize a repository workflow
- Create CD workflows that matches the team's needs and behaviors
- Use the repository's source code to build artifacts and store them in the GitHub Packages
- Save repository build artifacts
- Access saved build artifacts

**Phase 5: Continuous Delivery**
  > **The goal of Phase 5 is to Create two deployment workflows using AWS or Azure.**
  1. Go to the `Continuous Delivery` [actions module](https://lab.github.com/githubtraining/github-actions:-continuous-delivery)
  1. In this phase, you’ll learn how to:

- Create two workflow files
- Configure AWS S3 for deployment
- Use secrets to store tokens
- Deploy to staging and production
- Practice using GitHub Actions
