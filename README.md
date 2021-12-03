re# Recipe-Community-Backend
Django project for Recipe-Community-Backend website


# Contribution Guidelines

1. Fork this repo
2. Clone your forked repo `git clone`
3. Add the main repo as upstream `git remote add upstream {url}`
4. Make your changes and push to your(forked) repo.
5. Create a pull request from github to main repo.

To get some changes from main repo `git pull upstream`

__*NOBODY SHOULD DIRECTLY PUSH TO THE MAIN REPO.*__

There will be 2 branches
- main
- dev

_Apart from the 2 branches above you can create as many branches as you want._

__*NOBOBY SHOULD MAKE PULL REQUEST TO MAIN BRANCH. All changes should be made to dev.*__


# Folder structure
```
 |- .env.example (contains the sample format for the .env file)
 |- <django_project_name>
 |- <django_app_1>
 |- <django_app_2>
```
OR
```
<django_project_name>
 |- .env.example (contains the sample format for the .env file) 
 |- <django_project_name>
 |- <django_app_1>
 |- <django_app_2>
```
_Apart from this you can create any folders if you want._

# Important Notes
- Commits and pull requests should be made with proper descriptive messages.
- Do NOT commit or push any sensitive info such as passwords or emails in the code. Such data should go in the .env file, and a sample empty entry for the same should be added for the same in .env.example
