[Luma Shop](https://docs.google.com/spreadsheets/d/1bi5vlwV_ctLxJHSFebDoALSM2Km6bV_XwsXmPkGe0Tw/edit?usp=sharing). 
# Luma Shop E2E

## Introduction and goals of the projects
 
Main goal of the project is to get familiar with E2E testing. The topic is quite wide and can be separated into few phases. First of all I started clicking and scrolling the website, checking functionalities. Then I try to imagine what functionalities, from user perspective can be treated as key paths. I chose some of them for testing:
- Registration
- Logging
- Searching for products
- Adding products to cart
- Update user date 
- Additional functionalities

I chose the Luma Shop demo for testing because this website is a demo intended for testing purposes and also free. Similar websites are mostly to read only. While Luma Shop is more interactive - you can create a new account, update user date, add items to cart, update cart.
Shopping issue is my favorite as probably  most  internet users nowadays. 

## Manual Testing

To create tests cases I chose Google sheets. This tool is convenient to upload  create work by simple link. The Goal of manual testing is to check how the system works  correctly. While creating test cases I focus on usability. Test cases should be usable - should be written unambiguous that test cases can be executed not only by the author. Nowadays many testers work on many projects at the same time so it's important. Test scenario can mitigate human factor because there is no need because executed are pase on unambiguous scenarios.Not base on individual  tester approach. Already written  test cases according to regression testing are also convenient because can be repeated many times. 

## Conclusion I
I found two bugs in my project. One of these errors occurred when attempting to change the postal code; despite entering an incorrect code format, the system still made the change. Another error occurred in the search section, where entering "women's top" displayed not only tops but also other items.

## Automated testing
The best way to omit human factor are automated testing. To create automated testing you have invest time and effort. The tester should have knowledge about programming. Writing automated test cases consumes more time because you have to write classic test case and after that some code to automate that test case. The biggest benefit of automated testing is that you can execute many test case in just a few seconds. So it's really quick.

## Conclusion II
But not everything can be automated.We can image some examples that only human can test. One of this examples is uploading a photo, only humans can verify if the photo presents the desired object or person. In some cases manual testing is still important.
