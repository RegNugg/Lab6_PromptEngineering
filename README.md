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

Response:

<img width="1091" height="631" alt="imatge" src="https://github.com/user-attachments/assets/d8d97943-4af3-4c36-a416-0746109066bf" />

<img width="1209" height="436" alt="imatge" src="https://github.com/user-attachments/assets/fc6c2048-8b1c-4004-84aa-04665545b6cf" />


3.

Can we check if it works?

Response:

<img width="1180" height="569" alt="imatge" src="https://github.com/user-attachments/assets/3a273c3e-b37c-45e4-931a-caf89ce3b58f" />

<img width="873" height="218" alt="imatge" src="https://github.com/user-attachments/assets/91604d2b-0d46-48c5-92f6-a520e6e694b0" />

4.

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

Response:

<img width="1261" height="443" alt="imatge" src="https://github.com/user-attachments/assets/e2ce89c0-62e8-45e7-b30b-3ef8c0a04d5e" />


5.

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

Response:

<img width="1121" height="486" alt="imatge" src="https://github.com/user-attachments/assets/293c367b-cd07-4581-b04f-7c8d6ab20b7b" />


6.

It just shows a blank page with nothing on it. (Result: dev_test.html)

Response:

<img width="1000" height="407" alt="imatge" src="https://github.com/user-attachments/assets/618b00aa-e3b3-4664-8964-90a0cf90ea7c" />


7.

Now what's the next move?

Response:

<img width="1164" height="507" alt="imatge" src="https://github.com/user-attachments/assets/36870fe7-172c-4d0b-b0f8-0a5a10dccc3e" />

<img width="1153" height="348" alt="imatge" src="https://github.com/user-attachments/assets/b0f197a3-ce83-497a-9ce5-a997b39903b0" />


8.

Ok so reloading the page logs me out and whenever i log in again the reservation isn't there anymore, we only need to fix those 2 issues (Result: dev_test_fixed.html).

Response:

<img width="1254" height="644" alt="imatge" src="https://github.com/user-attachments/assets/8d403231-38ed-4b56-8b2c-8047b339a352" />

<img width="1185" height="523" alt="imatge" src="https://github.com/user-attachments/assets/3cab9a38-d603-4cb1-8b60-a5b8b7755273" />

<img width="1197" height="574" alt="imatge" src="https://github.com/user-attachments/assets/07058492-a4e6-4c57-a2d3-299b2bf1da79" />



Learned:

- Defining context and boundaries is the most important part about working with AI's . It is important to determine what the AI can and cannot edit, delete or add. Also giving the initial layout of folders and files (and their contents preferably) so the AI can understand where and how to act.
- Especifying the task is also very important, i.e. giving steps and specific subtasks, unless we want to give the AI absolute freedom.
- AI won't do everything right and could leave duplicated and unpolished code, so reviewing will be useful, even if it's sharing the code with another AI.
