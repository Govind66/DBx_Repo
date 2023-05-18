# Databricks GitHub Repo Operations
Databricks supports Git integration. In this tutorial, we will talk about how to do GitHub repo operation on the Databricks platform. You will learn:

* How to enable files other than notebooks in the Databricks repo?
* How to create a branch on Databricks?
* How to create a notebook in Databricks repo?
* How to push updates to a remote repository?
* How to create and merge a pull request?
* How to pull remote repository changes into Databricks?
Let’s get started!

## Step 1: Enable Files In Repos
Databricks Repos only sync notebooks with a remote Git repository by default. To allow other file formats such as .py, .csv, and .md in the Repo, we need to change the Repos settings in the Admin Console.

### Step 1.1: Open the Admin Console by clicking Settings, then Admin Console.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*EA7_Ruit_b1Q9i8p.png" width="500" height="300" align="middle">
</div>
### Step 1.2: Click Workspace Settings on the menu.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*Ki5dCG6H92rkeY-G.png" width="750" height="100" align="middle">
</div>

### Step 1.3: Go to the Repos section and enable Files in Repos. After it is enabled, we can sync any file type with the remote Git repository. We can also view and edit text files in the UI.

<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*Ph4tQGlvoCs_DwuN.png" width="200" height="200" align="middle">
</div>

## Step 2: Create A Branch On Databricks
In the second step, we will create a branch on Databricks.

### Step 2.1: Click Repos, then the user name, and main.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*jtf3ltBilzG8Fifm.png" width="500" height="300" align="middle">
</div>

### Step 2.2: Type a branch name and press the enter key to create the branch.

<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*7HYKgo3jFMAAxvB6.png" width="500" height="300" align="middle">
</div>
### Step 2.3: To switch between branches, click the downward arrow and select the branch name. We selected the test_branch here. Click the Close button to close the window.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*fGfroRTZee2TBS0Z.png" width="500" height="300" align="middle">
</div>

## Step 3: Create A Notebook In Databricks Repo
In the second step, we will create a new notebook in the test branch.

There are three ways to create a new notebook in the repo, creating a notebook from scratch, importing an existing notebook, or cloning a notebook from Workspace.

### Step 3.1: To create a notebook from scratch, go to Repos, user name, click the downward arrow near the branch name, select Create, then Notebook.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*NryMc_huEb0rJvdH.png" width="500" height="300" align="middle">
</div>

### Step 3.2: To import an existing notebook, go to Repos, user name, click the downward arrow near the branch name, then select Import.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*EPVIG3aZi6iDqoUy.png" width="500" height="300" align="middle">
</div>

We can either import a file or import from a URL.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*zJhL4ofIIb4oGV3O.png" width="500" height="300" align="middle">
</div>

### Step 3.3: To clone a notebook from the Workspace, go to Workspace, then user name. Click the downward arrow next to the notebook name and select Clone.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*ZMl710J0shc5mXLo.png" width="500" height="300" align="middle">
</div>

A new window will pop up. Give the cloned notebook a new name, then select Repos, user name, and the repo name. Click the blue Clone button to clone the notebook.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*aYC82Bk3II0ozUmj.png" width="500" height="300" align="middle">
</div>

### Step 3.4: To check if the notebook has been created, go to Repos, user name, then click the repo name. We can see that notebook has been successfully cloned to the branch.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*_jW9CQcW42U-5AkV.png" width="500" height="300" align="middle">
</div>

## Step 4: Push Updates To Remote Repository
In the third step, we will push updates to the remote repository.

### Step 4.1: Click the branch name to open the repo window. We can see that the newly added example notebook is shown as the changed file. Provide a summary and click the blue Commit & Push button.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*ezOjfoWZ9z7BNtE3.png" width="500" height="300" align="middle">
</div>

## Step 5: Create And Merge Pull Request
### Step 5.1: Go to the GitHub repo that is connected to Databricks, and you will see a message about the push. Click the green Compare & pull request button to open a pull request.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*oBuZMblDio3NjZZC.png" width="500" height="300" align="middle">
</div>

### Step 5.2: On the Open a pull request page, click the green Create pull request button to create a pull request.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*Su-iT5K2aAVrnfX_.png" width="500" height="300" align="middle">
</div>

### Step 5.3: After the pull request is approved, click the green Merge pull request button.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*9imZ1YQePDmbYOWT.png" width="500" height="300" align="middle">
</div>

Then click the green Confirm merge button.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*X2rpXRg3Qn138wYt.png" width="500" height="300" align="middle">
</div>

### Step 5.4: After the merge is confirmed, we will see a purple Merged button showing that the pull request is successfully merged and closed. We can click the Delete branch button to delete the branch.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*bpv19TeviP11q89V.png" width="500" height="300" align="middle">
</div>

### Step 5.5: Click the repository name, and we can see the notebook show up in the repository.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*UC8-vVVCy-o2SXjA.png" width="500" height="300" align="middle">
</div>

### Step 5.6: Go to Databricks and switch to the main branch, we can see the newly added notebook now show up in the main branch.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*bxjF7LfpLZHOKipV.png" width="500" height="300" align="middle">
</div>

### Step 6: Pull Remote Repository Changes Into Databricks
In step 6, let’s make some changes to the README file on GitHub, and pull the changes into Databricks.

## Step 6.1: Go to the GitHub repository for Databricks and click the pencil icon for the README file.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*34LcUvyhGRtdirya.png" width="500" height="300" align="middle">
</div>

### Step 6.2: I added the sentence “This is a new sentence added in GitHub.” and click the green Commit changes button.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*XRLLZY2A_Eivgkl-.png" width="500" height="300" align="middle">
</div>

### Step 6.3: Go back to Databricks and click Repos, user name, then main. In the popup window, click Pull.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*YCF5bDc1SMvsoSKS.png" width="500" height="300" align="middle">
</div>

### Step 6.4: A warning window pops up and ask if we want to “Preceded with pulling?”, click the blue Confirm button to start pulling the changes.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*S74enIMIOowHLzEM.png" width="500" height="300" align="middle">
</div>

### Step 6.5: After finishing pulling the changes, close the repo window then click the README file.
<div align="center">
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*JY99oq5RHZ88HmL5.png" width="500" height="300" align="middle">
</div>
We can see that the new sentence we added on GitHub are pulled into Databricks.

