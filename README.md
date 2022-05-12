# kipa-result-publisher

Bash script for publishing https://github.com/partio-scout/kipa results to Github.

## Set up envs

Replace values with your own.

```
touch .env
echo HOST="localhost" >> .env
echo PORT="3000" >> .env
echo EVENT_NAME="testikisa" >> .env
echo RESULT_REPO_DIR="/Users/pekkine/testikisa-results" >> .env
```

## Set up git repo

Create `RESULTS_REPO_DIR` and a git repo

# Usage

Give kipa specific class numbers as arguments, for example

`./publish 23 24 25`