Lab6_PromptEngineering

GitHub link: https://github.com/RegNugg/Lab6_PromptEngineering

Prompts used:
---------------------------CLAUDE CODE---------------------------
1.

Choose one of the 4 specifications given to develop an applications with visual studio code with GitHub copilot activated. 

Make the copilot writes you the code of the application (in React, java script or the technology you also do your final project) that complies with the given functional requirements and user stories.

Create a GitHub repository and to progressive commits as you keep refining the application iterativelly by giving more details to copilot with more specific prompts.

Document what prompts you give to copilot to get the code you want.

Submission:

    The code inside the GitHub repository
    README with:
        Used prompts
        Screen shoots of the result of the application 
        Lessons learn on the us of copilot

The submission documentation has to be in the GitHub repository, but also submit in here the README file within the deadline. Make sure the README puts the link to GitHub repository, to have it handy to go in.

This activity is done and submitted in teams. The time needed to resolve is expected to be less than the class session. But you have until the end of the day today to submit it.

(Also gave the file UserStories_Reserves_de_Biblioteca-ENG.pdf)

--------------------------GITHUB COPILOT--------------------------
2.

Please read these files and check the app structure, we need the ability to log in and the ability to log out, taking into account that we want data persistence, meaning once you register that info is saved for future log ins. (added the initial Claude README and the initial LibraryReservations.jsx)

3.

This is the terminal, I got this error:
didac@DESKTOP-PCEPB40:/mnt/e/Universitat/SoftEng/Lab6_PromptEngineering$ python -m http.server 5500
Command 'python' not found, did you mean:
  command 'python3' from deb python3
  command 'python' from deb python-is-python3
didac@DESKTOP-PCEPB40:/mnt/e/Universitat/SoftEng/Lab6_PromptEngineering$ python3 -m http.server 5500
Serving HTTP on 0.0.0.0 port 5500 (http://0.0.0.0:5500/) ...
127.0.0.1 - - [27/May/2026 15:43:10] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [27/May/2026 15:43:10] code 404, message File not found
127.0.0.1 - - [27/May/2026 15:43:10] "GET /favicon.ico HTTP/1.1" 404 -

4.

This is the terminal, I got this error:
didac@DESKTOP-PCEPB40:/mnt/e/Universitat/SoftEng/Lab6_PromptEngineering$ ls -la
python3 -m http.server 5500
total 76
drwxrwxrwx 1 didac didac  4096 May 27 15:42 .
drwxrwxrwx 1 didac didac  4096 May 27 15:04 ..
drwxrwxrwx 1 didac didac  4096 May 27 15:35 .git
-rwxrwxrwx 1 didac didac 21595 May 27 15:38 LibraryReservations.jsx
-rwxrwxrwx 1 didac didac  7939 May 27 15:33 README.md
-rwxrwxrwx 1 didac didac 44649 May 27 15:42 dev_test.html
Serving HTTP on 0.0.0.0 port 5500 (http://0.0.0.0:5500/) ...
127.0.0.1 - - [27/May/2026 15:44:09] "GET /dev_test.html HTTP/1.1" 200 -
127.0.0.1 - - [27/May/2026 15:44:12] code 404, message File not found
127.0.0.1 - - [27/May/2026 15:44:12] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [27/May/2026 15:44:32] "GET /dev_test.html HTTP/1.1" 304 -

5.

It just shows a blank page with nothing on it. (Result: dev_test_fixed.html)

6.

Now what's the next move?

7.

Ok so reloading the page logs me out and whenever i log in again the reservation isn't there anymore, we only need to fix those 2 issues
