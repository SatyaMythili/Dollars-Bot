# For Developers: From the Developers of DollarBot

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#function-documentation">Function Documentation</a></li>
    <li><a href="#testing">Testing</a></li>
    <li><a href="#code-coverage">Code Coverage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#code-documentation">Code Documentation</a></li>
    <li><a href="#how-to-contribute">How to Contribute</a></li>
    <li><a href="#future-roadmap">Future RoadMap</a></li>
  </ol>
</details>

## Code Documentation by Functionality

For a detailed explanation of the code, follow the links below:

<ol>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/code.md">Main Code File</a></li>
    <b> Features: </b>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/add.md">Add</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/budget_delete.md">Budget Delete</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/budget_update.md">Budget Update</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/budget_view.md">Budget View</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/delete.md">Delete</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/display.md">Display</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/estimate.md">Estimate</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/graphing.md">Graphing</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/helper.md">Helper</a></li>
    <li><a href="https://github.com/aditikilledar/dollar_bot_SE23/blob/main/docs/history.md">History</a></li>
  </ol>


## Testing

We use pytest to perform testing on all unit tests together. The command needs to be run from the home directory of the project. The command is:
```
python run -m pytest test/
```

## Code Coverage

Code coverage is part of the build. Every time new code is pushed to the repository, the build is run, and along with it, code coverage is computed. This can be viewed by selecting the build, and then choosing the codecov pop-up on hover.

Locally, we use the coverage package in python for code coverage. The commands to check code coverage in python are as follows:

```
coverage run -m pytest test/
coverage report
```


## How to Contribute

We would be happy to receive contributions! 

For any feedback, issues, or bug reports, please create an issue

## Future RoadMap

- More content can be added for the way notifications can be displayed on the user front. This can be done to make the UI more interactive.
- Recurring expenses feature can be added for faster addition of expenses instead of following the whole process of everytime.
