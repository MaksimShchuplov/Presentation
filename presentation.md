# What is Continuous Integration.
*Build your team's agility with faster feedback. Because you only move as fast as your tests.*

Hi! I am Olga Kharkevich. I graduated from Gomel State Technical University in 2009. I've been working as an constructor engineer since 2009 till nowadays. I've been a student of the Rolling Scopes School since January of 2020.
**Continuous integration (CI)** is the practice of automating the integration of code changes from multiple contributors into a single software project. The CI process is comprised of automatic tools that assert the new code’s correctness before integration. A source code version control system is the crux of the CI process. The version control system is also supplemented with other checks like automated code quality tests, syntax style review tools, and more.
## Importance of CI.
In order to understand the importance of CI, it’s helpful to first discuss some pain points that often arise due to the absence of CI. Without CI, developers must manually coordinate and communicate when they are contributing code to the end product. This coordination extends beyond the development teams to the rest of the organization, as well. Product teams must coordinate when to sequentially launch features and fixes and which team members will be responsible.
The communication overhead of a non-CI environment can become a complex and entangled synchronization chore, which adds unnecessary bureaucratic cost to projects. This causes slower code releases with higher rates of failure, as it requires developers to be sensitive and thoughtful towards the integrations. These risks grow exponentially as the engineering team and codebase sizes increase.
### How CI can be used.
 CI is generally used alongside an agile software development workflow. An organization will compile list of tasks that comprise a product roadmap. These tasks are then distributed amongst software engineering team members for delivery. Using CI enables these software development tasks to be developed independently and in parallel amongst the assigned developers. Once one of these tasks is complete, a developer will introduce that new work to the CI system to be integrated with the rest of the project.
### CI vs Continuous Deployment vs Continuous Delivery.
Continuous integration, deployment, and delivery are three phases of an automated software release pipeline. These three phases take software from idea to delivery to the end user. The integration phase is the the first step in the process. Integration covers the process of multiple developers attempting to merge their code changes with the master code repository of a project.
Continuous Delivery is the next extension of continuous integration. The delivery phase is responsible for packaging an artifact together to be delivered to end users. This phase runs automated building tools to generate this artifact. This build phase is kept ‘green,’ which means that the artifact should be ready to deploy to users at any given time.
Usually Continuous Deployment is the final phase of the pipeline.

## Benefits and challenges of continuous integration.
CI is a valuable asset to a software producing organization. CI benefits are not limited to the engineering team but greatly benefit the overall organization. The following are some of the overall organizational benefits of CI.
- **Enable scaling**. CI enables organizations to scale in engineering team size, codebase size, and infrastructure.
- **Improve the feedback loop**. Faster feedback on business decisions is another powerful side effect of CI. Product teams can test ideas and iterate product designs faster with an optimized CI platform.
- **Enhance communication**. Overall engineering communication and accountability is improved with CI. By introducing pull request work flows tied to CI, developers gain passive knowledge share. Pull Requests allow Developers to observe and comment on code from other team members. Developers can now view and collaborate on feature branches with other developers as the features progress through the CI Pipeline.
- **Technology learning curve**. CI functionality comes with a list of supportive technologies that may be learning curve investments for the team to undertake. These technologies are version control systems, hosting infrastructure, and orchestration technologies.

## CI best practices.
- **Test Driven Development**. Test Driven Development (TDD) is the practice of writing out the test code and test cases before doing any actual feature coding.
- **Pull requests and code review.** Pull requests are a critical practice to effective CI. A pull request is created when a developer is ready to merge new code into the main codebase.
Pull requests and code review are a powerful tool to foster passive communication and knowledge share among an engineering team. This helps guard against technical debt in the form of knowledge silos, where specific engineers are the only stakeholders for certain features of a code base.
- **Optimize pipeline speed.** It is a best practice to measure the CI pipeline speed and optimize as necessary. A faster CI pipeline enables a faster product feedback loop. Developers can rapidly push changes and experiment with new feature ideas to help improve the user experience

## Getting started with continuous integration.
The foundational dependency of CI is a version control system (VCS). If the target code base for a CI install does not have a VCS, step one is installing a VCS. The absence of a VCS should be very unlikely on modern codebases. Git is major VCS.
Once version control is in place, finding a version control hosting platform is the next move. Most modern version control hosting tools have support and features built in for CI. Some popular version control hosting platforms are **Bitbucket**, **Github**, and **Gitlab**.
## Summary.
If your organization has a multiple-developer software team and is not using CI, this is an opportunity to truly enhance your team’s quality of life. CI will help your engineering org execute quicker and more effectively.
### Thank you for your attention!

