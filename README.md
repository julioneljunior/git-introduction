
# Tuntscorp Git Introduction
This is a git introduction project, to employees with no experience. 

In this project all employee have a file with your information in specific contracts folders.

To complete this introduction, send the pull request url of your information file added in your respective contract type folder.

## Steps:

<details>
  <summary> 
    1. Clone repository 
  </summary>
  
To clone this repository:
#### 1.1. click in 'download or clone' button.
![download_or_clone_image](/md-images/001-clone_or_download.png)

#### 1.2. Copy the repository url.

![clone_url](/md-images/002-clone-url.png)

#### 1.3. Open Git Bash ( download link -> https://git-scm.com/downloads)
#### 1.4. Clone repository to your computer.

```
git clone '{repository_url}' // repository_url = url copied from step2
```
#### 1.5. Clone repository successful
</details>
<details>
  <summary>
    2. Create a branch
  </summary>
  
To create a new branch:
#### 2.1. Open Git bash
#### 2.2. Create a new branch with your name.
```
git checkout -b '{name_of_the_branch}' // name_of_the_branch = {yourname}+employee-document.
```
#### 2.3. Branch sucessful created.
</details>
<details>
  <summary>
    3. Added your information file
  </summary>
  
#### 3.1. Create your file taking into consideration your contract with the company (intern, clt or partner) and use the example.txt file to see what informations do you have insert.
#### 3.2. Creation with name format -> ```{firstName.LastName.txt}```
#### 3.3. Include your informations in the file
#### 3.4. Information file sucessful created.
</details>
<details>
  <summary>
    4. Make a push of your branch
  </summary>
  
#### 4.1. Open git bash
#### 4.2. Insert your Name and Email to represent your actions in this git project.
```
git config user.email {Your email}
git config user.name {Your name}
```
#### 4.3. Add your file to commit
```
git add ./employees/{your contract}/{yourname}.txt
```

#### 4.4. Add a new commit with the commentary of what represents your actions on repository
```
git commit -m 'Feat({yourname}.txt): Added my information file.'
```
#### 4.5. Create a push of your local commits
```
git push origin {your_branch_name}
```
</details>
<details>
  <summary>
    5. Create a Pull Request
  </summary>
  
#### 5.1. Open the repository website, open the 'Pull Requests' page, click in the 'New pull request' button.
![pull_request](/md-images/009-pull-request-page.png)

#### 5.2. Select your branch in 'compare or head' selector
![compare_branchs](/md-images/011-compare-branchs.png)
#### 5.3. Review your alterations and click 'Create Pull Request' button

![review_modifications](/md-images/012-review-modifications.png)

#### 5.4. Insert a title and description (you have the list of commit messages) and added a reviewer to analyze and approve or reject your pull request.
![review_modifications](/md-images/014-pull-request.png)

#### 5.5. Click 'Create pull request' button
</details>
