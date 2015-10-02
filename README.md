# Solving your first Lab

## Objectives

1. Open a lab by clicking "Open" on this page on Learn.co.
2. Run the lab's tests with the `learn` CLI command.
3. Make a change to your local copy of this lab.
4. Pass the tests using the `learn` CLI command.
5. Submit the passing lab with the `learn submit` CLI command.

## Instructions

This lab is just about practicing the lab workflow on Learn using the `learn` CLI.

1. Click on the "Open" link on the lab toolbar above.

SCREENSHOT

After you click on this, a new tab should open with your Nitrous container. At the same time, behind the scenes we are forking the lab and clone it to your container. 

SCREENSHOT

2. After the lab is opened, your Nitrous console should already be in the lab's directory. You may need to click through the file 1 or 2 levels deep to find the labs' files in the "labs" directory.

SCREENSHOT

This setup—your console open in the lab's directory and the lab directory open in the file browser—that's the state you want to be in when working on a lab on Learn. It means you're ready.

3. In the console, run the test suite by typing `learn` and hitting enter. You'll see something simlar to:

SCREENSHOT

You can see your test is currently failing, which is fine, we haven't done any work yet, so it makes sense.

The failure reads: `Make sure you have added a new file or edited edit-me.txt`

4. To pass this lab, either make any change to the content of `edit-me.txt` or create a new file.

You can open `edit-me.txt` and you'll see it is currently empty. Add anything to that file, save the file, and then run `learn`, everything should pass.

You can also pass this lab by creating a new file. From your console, you can run `touch new-file` to create a new file. If a new file is added to this lab, when you run `learn`, your tests should pass.

SCREENSHOT

5. Once your local tests are passing, you can submit this lab by running `learn submit` from your terminal.

SCREENSHOT

You should see this lab pass on Learn.co. Congratulations! You've just solve your first lab. 
