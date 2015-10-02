# First Lab Ruby Learn Cli Osx

## Objectives

1. Open a lab by clicking "Open" on this page on Learn.co.
2. Run the lab's tests with the `learn` CLI command.
3. Make a change to your local copy of this lab.
4. Pass the tests using the `learn` CLI command.
5. Submit the passing lab with the `learn submit` CLI command.

## Instructions

This lab is just about practicing the lab workflow on Learn using the `learn` CLI.

1. Click on the "Open" link on the lab toolbar above.

![Open Button](https://dl.dropboxusercontent.com/s/6hmrbrtcf0gssev/2015-09-30%20at%207.11%20PM.png)

After you click on this, your Terminal should popup and open the lab locally by forking it on GitHub, cloning your fork, and `cd`ing into the lab's directory, and opening your editor.

![Learn Open](http://learn-co-videos.s3.amazonaws.com/learn-co-orientation/open-from-learn-co.gif)

2. After the lab is opened, your terminal should be in the lab's directory and your text editor should be opened.

![Work mode](https://dl.dropboxusercontent.com/s/je5pazo2edy5cwl/2015-09-30%20at%207.34%20PM.png)

This setup, a terminal in the lab's directory and the lab directory open in an editor like Sublime or Atom, that's the state you want to be in when working on a lab on Learn. It means you're ready.

3. From your terminal, run the test suite by typing `learn` and hitting enter. You'll see something simlar to:

![Failing Test](https://dl.dropboxusercontent.com/s/0ik01a1urmuw7o6/2015-09-30%20at%207.46%20PM.png)

*Note: My prompt is `// ♥`, yours might be different. You'll see a terminal prompt generally represented by a `$`. That indicates you're suppose to be typing in terminal.*

You can see your test is currently failing, which is fine, we haven't done any work yet, so it makes sense.

The failure reads: `Make sure you have added a new file or edited edit-me.txt`

4. To pass this lab, either make any change to the content of `edit-me.txt` or create a new file.

You can open `edit-me.txt` and you'll see it is currently empty. Add anything to that file, save the file, and then run `learn`, everything should pass.

You can also pass this lab by creating a new file. From Terminal, you can run `touch new-file` to create a new file. Or use your text editor to create a new file and save it. If a new file is added to this lab, when you run `learn`, your tests should pass.

![Passing Tests](https://dl.dropboxusercontent.com/s/op46jyoc228ji62/2015-09-30%20at%207.53%20PM.png)

5. Once your local tests are passing, you can submit this lab by running `learn submit` from your terminal.

![learn submit](http://learn-co-videos.s3.amazonaws.com/learn-co-orientation/learn-submit-cli-osx.gif)

You should see this lab pass on Learn.co, congratulations!
