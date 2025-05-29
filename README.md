# kipa-result-publisher

Bash script for publishing https://github.com/partio-scout/kipa results to Github.

## Set up envs

Replace values with your own.

```
touch .env
echo HOST=localhost >> .env
echo PORT=3000 >> .env
echo EVENT_NAME=Kaaos_testikisa >> .env
echo RESULT_REPO_DIR="/Users/pekkinev/kaaos-results" >> .env
```

## Set up git repo

Create `RESULTS_REPO_DIR` and a git repo

# Usage

Arguments: 

1. Kipa specific class number
2. Output filename

For example: 

```
./publish 1 oranssi.html
./publish 2 vihrea.html
./publish 3 purppura.html
```
