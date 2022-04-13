## Setting up the Solar Eclipse Repo

First thing you want to do is Install GitKraken
https://www.gitkraken.com/download
This is not really a requirement, but it will make it easier. You will need to make a Github.io account if you do not already have one.
https://github.com/
With this done, you will want to login on gitkraken using this github account.
You will then want to make a "fork" of the following repository.
https://github.com/DiscoTrayStudios/Solar
After forking the repository you will want to clone it onto your computer. This is done by going onto gitkraken, pressing "file" --> "clone repo" --> "GitHub.com" and then you can choose where it will be cloned on your computer and the repository to clone. You will want to clone the "Solar" repository under your username.

## Running the website locally

Install Visual Studio Code
https://code.visualstudio.com/
Install Ruby and Jekyll
https://jekyllrb.com/docs/installation/windows/
Open the Solar repository you previously cloned using Visual Studio Code (File --> Open Folder)
(When you look at individual files after opening this repo you may notice that it gives you suggestions on plugins to install, I recommend you do as it recommends most of the time, but if you have any questions feel free to ask)
Open the terminal (Terminal --> New Terminal)
Run the following commands in the terminal:

- gem install jekyll bundler
- bundle
- bundle update
Now you should be able to run the website using:
- bundle exec jekyll serve

Again if there are any questions or issues please reach out.
