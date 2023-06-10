Configuration files and requirements for use with [yatm](https://github.com/audrow/yatm).

## Usage

Export necessary environment variables for `yatm`.
```bash
cd ~/
git clone https://github.com:osrf/ros2_test_cases
export YATM_TEST_CASE_CONFIG_PATH=$HOME/ros2_test_cases/garden-release/test-case.config.yaml
export YATM_REQUIREMENTS_DIRECTORY_PATH=$HOME/ros2_test_cases/garden-release/requirements
export GITHUB_REPO_OWNER=gazebosim
export GITHUB_REPO_NAME=garden-tutorial-party
export GITHUB_TOKEN=<your-github-token>
```

Follow instruction [here](https://github.com/audrow/yatm#how-to-use-this-repository) to create and upload test cases.
