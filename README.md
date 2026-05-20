# Check Your Understanding

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.  
**Answer:** Within a Github action that runs whenever code is pushed. This is the best option because it automatically tests your code after every push in a clean environment. This way, bugs are caught early on and it is easy to understand which chunk of code the bug is in and what is affected. You can also configure the action so that the code is not merged if it does not work, so that the repo only has working code. This is especially important if this is open source or a public repo. Running locally requires manual testing and it is not as guraranteed to be consistent as automated testing. Testing at the end groups all of the bugs and code together, which makes the debugging process messy and more difficult.  

2) Would you use an end to end test to check if a function is returning the correct output?  
**Answer:** No. End to end testing is used to simulate user actions, not to check if an output is correct. That would be the job of a unit test, which would be a much faster process.  

3) What is the difference between navigation and snapshot mode?  
Navigation mode analyzes a page right after it loads from scratch. It will provide an overall performance metric. In contrast, snapshot mode analyzes a page in its current state only, so it's used for finding accessibility issues but it can't analyze things like load-time performance or JavaScript execution.  

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.  
**Answer:** Fix accessibility issues (increase the contrast of the yellow buttons, missing ARIA labels), improve SEO (making sure there are descriptive meta descriptions), and improve best practices (fix the console issues).  
