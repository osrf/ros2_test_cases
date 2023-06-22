## Config files for YATM to create issue tickets from requirements

## Setup
```bash
cd ~/
git clone https://github.com:osrf/ros2_test_cases
```

## Configuration
Configuration files and requirements for use with [yatm](https://github.com/audrow/yatm) are stored in release specific folders. Follow instructions [here](https://github.com/audrow/yatm#how-to-use-this-repository) to create and upload test cases. Before running any commands, a number of environment variables need to be set. These are documented below for each release.

### Humble

```bash
export YATM_TEST_CASE_CONFIG_PATH=$HOME/ros2_test_cases/config/humble/test-case.config.yaml
export YATM_REQUIREMENTS_DIRECTORY_PATH=$HOME/ros2_test_cases/config/humble/requirements
export YATM_DISTO_LABEL=humble
export GITHUB_REPO_OWNER=osrf
export GITHUB_REPO_NAME=ros2_test_cases
export GITHUB_TOKEN=<your-github-token>
```

### Iron

```bash
export YATM_TEST_CASE_CONFIG_PATH=$HOME/ros2_test_cases/config/iron/test-case.config.yaml
export YATM_REQUIREMENTS_DIRECTORY_PATH=$HOME/ros2_test_cases/config/iron/requirements
export YATM_DISTO_LABEL=iron
export GITHUB_REPO_OWNER=osrf
export GITHUB_REPO_NAME=ros2_test_cases
export GITHUB_TOKEN=<your-github-token>
```

### Jazzy

```bash
export YATM_TEST_CASE_CONFIG_PATH=$HOME/ros2_test_cases/config/jazzy/test-case.config.yaml
export YATM_REQUIREMENTS_DIRECTORY_PATH=$HOME/ros2_test_cases/config/jazzy/requirements
export YATM_DISTO_LABEL=jazzy
export GITHUB_REPO_OWNER=osrf
export GITHUB_REPO_NAME=ros2_test_cases
export GITHUB_TOKEN=<your-github-token>
```
