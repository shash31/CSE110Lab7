## Team Members

1. Phyo Thant
2. Shash

## Lab Questions

1.  Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

    Choice: Within a Github action that runs whenever code is pushed. Reason: It ensures that all of the tests are automatically checked everytime a new feature or bug has been fixed. It also catches if the code disrupted the pre-exisiting features and keep the main branch clean.

2.  Would you use an end to end test to check if a function is returning the correct output? (yes/no)

    No as an end to end test checks the entire application from the perspective of the user and a function returning the correct output should be tested with a smaller unit test

3.  What is the difference between navigation and snapshot mode?

    Navigation audits the full page load as like how the user visit the website. It tests the overall performace such as performace metric calculation on speed / unneccessary codes / image compatibility / assessibility / search engine optimization.

    Snapshot records as I manually click things, and it calculates the metric upon the interactions that I made. It tests the blocking time / layoutshifts / ineteraction to next paint.

4.  Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
    1.  images that are properly sized to the to reduce the file size of 518kib which can improves the load time
    2.  `<meta name="viewport"> ` is missing in the html. It optimizees the app for mobile screen sizes, and prevents 300ms delay to user input.
    3.  Images are being dynamically added to the page, it's better to preload the images in order to improve Largest Contentful Paint (LCP).
