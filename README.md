In my case, I have MacOs Big Sur running with zsh shell. The first thing you need to do is get the prefix of your npm-global path:

npm config get prefix
Then this will be return some thing like this:

/Users/your_user/npm-global
Copy this path, and add the /bin in the end -> /Users/your_user/npm-global/bin. Then we will export this path into the bash configs.

export PATH=$PATH:/Users/your_user/npm-global/bin 
I believe all yours global npm packages will work fine now.

export PATH=$PATH:/www/server/nodejs/v16.14.0/bin
