# Portfolio Workshop

The hugo theme used for this workshop is luizdepra's `hugo-coder` https://github.com/luizdepra/hugo-coder.

## Basic Setup Resources

### Github account Signup 
Sign up for an account at https://github.com/join

### Hugo Blog Themes
https://themes.gohugo.io/tags/blog/

### Netlify account Signup
https://app.netlify.com/signup (Use GitHub authentication to sign up quickly!!)

## Advanced Setup Resources
In the second half of the workshop, we will be working on setting up your local environment to be able to customise your blog!

### Downloading and Installing Git
#### Windows:
https://gitforwindows.org/
#### Mac (OSX):
https://git-scm.com/downloads
#### Mac with Homebrew:
```
$ brew install git
```
#### Linux:
```
$ sudo apt update
$ sudo apt upgrade
$ sudo apt install git
```

### Git Setup
```
$ git config --global user.name "Your name here"
$ git config --global user.email "your_email@example.com"
```

### Download and Install Hugo
#### Windows:
https://gohugo.io/getting-started/installing#windows
#### Mac (OSX):
https://gohugo.io/getting-started/installing#macos
#### Linux:
https://gohugo.io/getting-started/installing#linux

**NOTE:** Please make sure you download the `hugo_extended` version!!!!! Otherwise it will no worky :(

### Cloning your repository
1. Navigate to the folder of your choice
    ```
    $ cd <path-of-folder>
    ```
    e.g.
    ```
    $ cd ~/Documents/Projects
    ```
2. Clone your repository
    ```
    $ git clone <repository-url>
    ```
    
### Reinstall the hugo-coder theme!
```
rm -rf themes/hugo-coder
git submodule add https://github.com/luizdepra/hugo-coder.git themes/hugo-coder
```

### Running your Code Locally
```
hugo serve -w
```

### Saving your Changes
```
$ git add .
$ git commit -m"<enter a message of what you did here>"
$ git push
```
#### Helpful explanation as to how git works!
![](static/images/git_explanation.gif)
