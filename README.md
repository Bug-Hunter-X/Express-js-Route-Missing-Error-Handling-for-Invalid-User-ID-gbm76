# Express.js Route Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input, specifically in this case, an invalid user ID.

The `bug.js` file shows the erroneous code, where a route handler fetches user data based on an ID passed in the URL.  If an invalid ID is used, the application crashes. 

The `bugSolution.js` file shows the corrected code with robust error handling, preventing crashes and providing a better user experience.