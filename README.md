# Footprint Messages
[![Ubuntu 22.04 Iron Build](https://github.com/roncapat/footprint_msgs/actions/workflows/iron.yaml/badge.svg?branch=iron)](https://github.com/roncapat/footprint_msgs/actions/workflows/iron.yaml)
[![Ubuntu 22.04 Rolling Build](https://github.com/roncapat/footprint_msgs/actions/workflows/rolling.yaml/badge.svg?branch=iron)](https://github.com/roncapat/footprint_msgs/actions/workflows/rolling.yaml)

Can be visualized in Rviz with [rviz_footprint plugins](https://github.com/roncapat/rviz_footprint_plugins) package.

# Pre-commit
This project uses [pre-commit](https://pre-commit.com/).  On Ubuntu, install it with:
```
sudo python3 -m pip install pre-commit
```
Then, enter the repository root and run :
```
pre-commit install
```
Now every time a commit is issued, a number of automated checks are done on code.
