# Charan Battula Lab Seven
## Questions
1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   - I would fit my automated tests in a Github actions that runs whenever code if pushed.  This is because it would ensure that even as we are developing, we are ensuring that the code is well written and functional
2. Would you use an end to end test to check if a function is returning the correct output? 
   - No, End To End is more for emulating user actions to make sure it is working.  Functional testing could be accomplished with unit tests looking for edge cases and proper back end behavior.
3. What is the difference between navigation and snapshot mode?
   - Navigation mode checks the page after a full load so it checks to see how to page is built and an overall performance of it.  The Snapshop mode checks the page in its current state so it is more for accessibility issues.
4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   - In our case, Lighthouse states that the perfomance is lackluster.  We could first reduce the execution and main thread work as they are taking a long time.  We could update the sizes and formats of the images are they may be causing loading issues.  Finally, we could save some of the text in the js file as it is unnecssary and some of it is not being used.