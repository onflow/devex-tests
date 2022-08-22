
# devex-tests

Contains scripts and github actions to run integration tests with devex tools
To run Github Action workflow locally, use <https://github.com/nektos/act> as so `act workflow_dispatch -e payload.json` </br>
On Apple M1 (ARM arch) use `act workflow_dispatch -e payload.json --container-architecture linux/arm64`
