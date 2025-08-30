hey there

this is cli type, a super fast and fun terminal app that helps you practice typing. it's built with rust and keeps things simple yet engaging. you'll get to practice typing actual rust code snippets while tracking your speed.

what does it do?
* shows you random rust code to type
* measures how fast you type (wpm)
* gives you instant feedback
* runs right in your terminal
* keeps things minimal and clean


how it works
when you start the app, you'll see something like this:

```
██████╗ ██╗   ██╗███████╗████████╗██╗   ██╗      ████████╗██╗   ██╗██████╗ ███████╗
██╔══██╗██║   ██║██╔════╝╚══██╔══╝╚██╗ ██╔╝      ╚══██╔══╝╚██╗ ██╔╝██╔══██╗██╔════╝
██████╔╝██║   ██║███████╗   ██║    ╚████╔╝ █████╗   ██║    ╚████╔╝ ██████╔╝█████╗
██╔══██╗██║   ██║╚════██║   ██║     ╚██╔╝  ╚════╝   ██║     ╚██╔╝  ██╔═══╝ ██╔══╝
██║  ██║╚██████╔╝███████║   ██║      ██║            ██║      ██║   ██║     ███████╗
╚═╝  ╚═╝ ╚═════╝ ╚══════╝   ╚═╝      ╚═╝            ╚═╝      ╚═╝   ╚═╝     ╚══════╝

Welcome to RUSTY-TYPES: Test your Rust coding speed and accuracy
Press 'Esc' to exit anytime. :)

Type the following Rust code:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Arc::new(data)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Start typing here:
```

just type what you see and the app will:
* check each character as you type
* let you use backspace if you make a mistake
* show your typing speed when you finish
* let you quit anytime with ESC

tech stuff
built using:
* rust 2021
* crossterm for terminal manipulation
* rand for picking random code snippets

want to run it locally?
```bash
git clone https://github.com/waliilaw/Rusty-type
cd Rusty-type
cargo run
```

want to help?
feel free to:
* try it out and let me know what you think
* suggest new features
* help fix bugs
* add more code snippets

to contribute:
1. fork the repo
2. create your feature branch
3. make your changes
4. send a pull request

licensed under mit, so you can pretty much do whatever you want with it

need help?
just open an issue and i'll help you out
