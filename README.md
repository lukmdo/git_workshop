# Materials and Plans for the [Git Workshop](http://www.ignitekrk.com/events/17546014/)

## Scenarios should

- be created as a clan `branch` using `scenario_NAME` convention:

   `git symbolic-ref HEAD refs/heads/scenario_NAME
    rm .git/index
    git clean -fdx`
- have a `README` file with a scenario description
- have a `scenario.txt` with enumerated list of steps already taken(history) and what is expected 
- `repo` directory with all required files

## Scenario Solutions

- should be also a branch with `busted_scenario_NAME`
   `git co -b busted_scenario_NAME`
- should have a `scenario_solution.txt` explaining steps taken to meet the expectations
- all the steps taken should get committed    


---
More in [IDEAS](https://github.com/ssspiochld/git_ws/tree/master/IDEAS.md) file.
