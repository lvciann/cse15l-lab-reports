1. logging into ieng6

   I have my ieng6 log in copied so typed `<command> + <v> + <enter>` to get `ssh l2valencia@ieng6.ucsd.edu`, I do it this way because I think it's quicker.
   
   <img width="629" alt="Screenshot 2024-02-27 at 11 26 58 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/64a0a74a-6f91-479a-a4db-e5148453f2d1">


2. Cloning fork of repository from Github

   Typed `git clone <command> + <v> + <enter>`, which produced `git clone git@github.com:lvciann/lab7.git` to access `lab7`. This is the ssh URL provided by github, which I got by pressing the "copy url to clipboard" button. I press the button instead of highlighting and using `<command> + <c>` because I think it's easier.
   <img width="506" alt="Screenshot 2024-03-11 at 2 55 18 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/6674c11a-8bd8-42c9-a7a7-e5e54185350b">

3. Running the tests, demonstrating that they fail

   typed `<cd la> + <tab> + <enter>`, which produced `cd lab7/` on the line. This is to enter the appropriate directory. Once in the `lab7` directory, I typed `<bash> + <t> + <tab> + <enter>` to get `bash test.sh` on the line. I used `<tab>` for both commands becuase I think it's quicker and I think I should be using as many shortcuts as I can for practice. The output said there was a failure, which was predicted.

     <img width="598" alt="Screenshot 2024-02-27 at 11 31 34 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/8595e971-1a21-46df-a2a5-b3719997cec1">

4. editing the code file to fix the failing test
   
      typed `<vim L> + <tab> + <.j> + <tab> + <enter>`, producing `vim ListExamples.java ` to edit `ListExamples.java`. Because I redid this part, I found out that the error I needed to edit was on line 44 so, I pressed `<4> + <4> + <shift> + <g> + <l> + <l> + <l> + <l> + <l>` to get to the character that I needed to delete. I like that we can delete things without being in "insert mode" on vim so I pressed `<x>` to remove the `1`. Then I pressed `<i>` to enter "insert mode" and pressed `<2> + <esc>` before I accidentally edit anything else. I then pressed `<:> + <w> + <q> + <!>` to save my work and exit.

   <img width="576" alt="Screenshot 2024-02-27 at 11 34 12 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/53db7bae-d660-4a69-87af-57b81905e162">

5. Running the tests, demonstrating they succeed
   
      On the command line, `bash test.sh` was up 2 in the command history so I pressed `<up> + <up> + <enter>`. I like using the up arrow keys alot, so I use them as much as possible. Both tests now succeed (:

   <img width="323" alt="Screenshot 2024-03-11 at 3 51 51 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/6aa049f6-11d2-493c-bece-69f2953c2048">

   
7. commiting and pushing the resulting change to github

   I typed `<git add> + <L> + <tab> + <.j> + <enter>`, which produced `git add ListExamples.java` on the command line. I don't think I can say how much I love the `<tab>` button, it makes everything so much easier.
   <img width="413" alt="Screenshot 2024-03-11 at 3 59 37 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/a0d69685-49a0-48fa-841b-794e1cf1a422">

   On the next line, I then typed `<git commit> + <-> + <m> + <"> + [my message] + <">` with the message "edited ListExamples.java". After I pressed the second `<">` to close my message, I pressed `<enter>`. On my first go with this lab, I had "edited files," but upon reflection, it would be best to be more specific so I chose to change it.

   <img width="520" alt="Screenshot 2024-03-11 at 4 07 51 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/be6fe847-6e6c-4197-ac5b-3a0b32fe64f1">

   After I made the commit command, I then typed `<git push> + <enter>` to push the commit to github. I initially had a hard time remembering which order the git commands went, then I realized it was in the commands after "git" were in alphabetical order.

   <img width="490" alt="Screenshot 2024-02-27 at 11 42 18 PM" src="https://github.com/lvciann/cse15l-lab-reports/assets/105315522/e9e23ed5-0975-4abd-8905-d78ad07f5bed">
