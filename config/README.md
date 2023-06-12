Configuration files and requirements for use with [yatm](https://github.com/audrow/yatm).Follow instructions [here](https://github.com/audrow/yatm#how-to-use-this-repository) to create and upload test cases. Before running any commands, a number of environment variables need to be set. These are documented below for each release.

## Humble

```bash
cd ~/
git clone https://github.com:osrf/ros2_test_cases
export YATM_TEST_CASE_CONFIG_PATH=$HOME/ros2_test_cases/humble-release/test-case.config.yaml
export YATM_REQUIREMENTS_DIRECTORY_PATH=$HOME/ros2_test_cases/humble-release/requirements
export GITHUB_REPO_OWNER=osrf
export GITHUB_REPO_NAME=ros2_test_cases
export GITHUB_TOKEN=<your-github-token>
```

