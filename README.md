## Platform Navigation Guide

This repository hosts guides on how the platform is used. The documents are ingested into Lara. The platform guides portal is hosted on github pages

## Setup

Clone the repository:
```bash
git clone git@github.com:Capital-Connect/documentation.git
```

## contribution
1. Add the documentation - add an `md` file following this structure

    ```md
        ## Documentation Index
        > Fetch the complete [documentation](https://capital-connect.github.io/index.md)
        > Use this file to discover all available pages before exploring further.

        # Name - the name of the documentation
        A briefe description of what the documentation is about

        ## Requirements (Optional)
        - list all the requirements a user need to navigate the feature

        ## Steps
        > List all the steps taken to use/navigate the feature

        ## Possible Issues
        - List what could possibly go wrong (error messages, when they occur)

        ## Possible Remedies
        - List the possible fixes to the issues. Always consider the user contacting the office if the issue persists 

        ## Next Steps
        - List the next steps a user would take after using the feature

        ## Suggestions
        - List what else the user can do at the end of the feature
    ```
2. Update the feature in the `index.md` file in the format

    ```md
    - [Name](Link): What it does
    ```