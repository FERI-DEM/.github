# FERI - DEM

### Description
It's a student project about ....

## Branches
Every code repositroy needs at least a `main` and `development` branch. 

The `main` branch should contain the latest, stable and production-ready version of the code.

The `development` branch, on the other hand, is used for ongoing work on new features and bug fixes. It is a branch separate from the main branch and provides a space for developers to make changes, test them and merge them into the main branch when they are ready for release.


## Branch naming conventions
- your_name/feat/ticket_name/branch_name
- your_name/fix/ticket_name/branch_name
- your_name/chore/ticket_name/branch_name

#### Examples
- Use this one if you are adding a new feature to the app
  
  `janez/feat/DEM-1/login`
  
- Use this one if you fixig a problem on the app

  `janez/fix/DEM-1/login`
  
 - Use this one if you are refactoring the app
 
   `janez/chore/DEM-1/refactor-class`

## Commit naming conventions
Use one of those 3 types as prefix for every commit
- `feat`
- `fix`
- `chore`

#### Examples
- Adding login page

  `feat: add login page`
  
- Fixing login page

  `fix: login page`
  
- Refactoring login page

  `chore: refactor login page`

## Workflow
- pull the latest changes to `develoment`
- create new branch from `development`
- commit your changes
- merge new changes from development to your branch (optional)
- push your branch to github
- go to github and open a pull request (your branch should merge into `development`)
