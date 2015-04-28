#Notes on code reviewing 

###Why review code? 
Learning to read code is as important as learning to write it. So, to assist your own learning and, incidentally, to help others.   
###How to review code 
By raising issues in a GitHub repo.     
If you are reviewing a Pull Request add line-comments: https://help.github.com/articles/commenting-on-the-diff-of-a-pull-request/ so that your feedback is contextual.  

###GitHub 
+Clone the repo; 
+Follow the instructions in the README.  

###Raise issues 
+If the code doesn't run when using `npm i && npm test`; 
+If the installation instructions are incomplete; 
+If the instructions for running tests are incomplete; 
+If the instructions for running the app are incomplete;
+If either the tests or the app fail to run; 
+If you don't understand the point of a test;
+If the code coverage is incomplete and it is not obvious why; 
+If any of the code fails linting tests (e.g. jshint);
+If you think the file structure is not clear;
+If you think any of the files are too long (~200+ lines);  
+If you think the code could be made more modular; 
+If you think the functions are not well-named; 
+If any of the functions look too long to you; 
+If you cannot follow the flow of control in the code; 
+If you think functions are too-deeply nested; 
+If you see any username/password credentials in the code.

