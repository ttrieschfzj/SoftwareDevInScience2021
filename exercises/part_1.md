# GitHub Agile Workflow

***In these exercises, we practice the basic GitHub workflow for contributing to a project.***

## Exercise I: Contribute to a Project

1. Fork the workshop repository to your own GitHub account.

2. Create a clone of the forked (your) workshop GitHub repository on your local machine.

3. Create a local branch to work on.

4. Apply any changes you like and add them to your local branch.

5. Commit your changes and push them back to your GitHub repository.

6. Issue a pull request against the workshop repository.

## Exercise II: Work in groups. Choose a developer to collaborate with!

1. Create a new local branch to work on.

2. Apply any changes you like and add them to your local branch.

3. Commit your changes and push them back to your GitHub repository.

4. Issue a pull request against your collaborator’s branch.

5. Let your collaborator review your pull request using GitHub's review workflow.

6. Let your collaborator merge your pull request.

7. Let your collaborator issue a pull request against the project 'main'!

8. (optional) Use the graphical repository browser gitk to display the changes in the repository.

## :+1: Hints ##

* Workshop repository: *https://github.com/gtrensch/SoftwareDevInScience2021*

* Cloning the forked repository: `git clone https://github.com/<your_GitHub_user_name>/SoftwareDevInScience2021`

* Gitk documentation: *https://git-scm.com/docs/gitk*

* git push GitHub authentication fails
 
  In August 2021 the support for password authentication was removed. Instead, a personal access token or an SSH key-based secure authentication must be used.
  - Create a user token: *https://github.com/settings/tokens*
  - SSH key
    
    - To create an SSH key run:
      
      `ssh-keygen -t rsa -b 4096`
    
    - Add the public key to your GitHub account: 
     
      https://github.com/settings/keys
    
    - To test SSH access, issue the following command:
      
      `ssh -T git@github.com` 
      
    - Enable the SSH URL: 
     
      `git remote set-url origin git@github.com:<your_GitHub_user_name>/SoftwareDevInScience2021`

