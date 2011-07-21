# Materials and Plans for the [Git Workshop](http://www.ignitekrk.com/events/17546014/)

## Scenarios Should

Be created as a clan `branch` using `scenario_NAME` convention:

    git symbolic-ref HEAD refs/heads/scenario_NAME
    rm .git/index
    git clean -fdx

Have a `README` file with a scenario description

Have a `scenario.txt` with enumerated list of steps already taken(history) and what is expected 

Have a `repo` directory with all required files

## Scenario Solutions Should

Be also a branch with `busted_scenario_NAME`

    git co -b busted_scenario_NAME

Have a `scenario_solution.txt` explaining steps taken to meet the expectations

Have all the steps taken be committed    


---
More in [IDEAS](https://github.com/ssspiochld/git_ws/tree/master/IDEAS.md) file.
