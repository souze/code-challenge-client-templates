# Different implementations for code-challenge clients

## Participate in code-challenge

If you are participating in a code-challenge, you can start by cloning this repository, then use the template of your favorite language

 ## Contribute
 
  Want to contribute with a new template implementation in a different language, or a different style? You're very welcome to.
  
  Here are some guidelines, that would be nice to follow for all template clients
  
  There is (TODO) a python stub-server in the stub-server directory, which can be used while developing your client, if you don't want to run the actual server.
  
  ### First run should yield a helpful error message
  
Likely, the first thing someone will do is to run the program. That should output information about how to set username/password, and where to write the user-code.
  
  ### Separate file where the user code goes
  
  ### No default username/password
  
  The user should be prompted, or instructed, the first time the client is run.
  
  Suggested ways to input username and password might be:
  
  * Command line flags
  * Environment variables
  * Hardcode it in the source code (just make sure the default values are not valid)
  
  ### Nice error prints
  
  It should be understandable what happened in the session, without the user having to spend time figuring out how to print json-data
  
  ### JSon decoder help
  
  If it's a dynamically typed language, the json decoding can be done already in the template. 
  If that's not possible, some useful libraries should be installed/imported, and possibly some comment about how to use it.
  Reading json decoding documentation should not be part of the challenge :)