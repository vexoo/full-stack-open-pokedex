If Python is used to code the application, some tools for CI setup include Flake8 for linting, Pytest for testing and setuptools for building.
Other Python tools for CI/CD would be for example Tox. Tox manages installs under different environments, such as different Python implementations, versions or installation dependencies.

Alternatives to Jenkins and Github Actions to set up CI include GitLab, CircleCI, Travis CI.

When it comes to choosing between self-hosted or cloud based environment. Self-hosted may have steep costs, both initial for hardware and maintenance, which could be a deciding factor for a small team.
One other key downside for a small team is time. Self-hosting requires time possibly learning how to setup, then setting up and especially maintaining, and I have my doubts a small team self-hosted services
are close to the quality of cloud-based services from Google or whoever else.
Benefits on self-hosting seem to focus on the ability to control the environment, and better security, since all the data is going to be on your own machines.

For a team of six people, I can't imagine cloud-based environment not being the correct choice. The team simply seems too small to handle the drawbacks of self-hosted environments