# Policy Expert - Home Code Assessment

We value the ability to model problems in software, so our first assessment will be around that subject. The exercise is to model and code a simple supermarket pricing solution. It is inspired on Pragmatic Dave’s Supermarket Kata - http://codekata.com/kata/kata01-supermarket-pricing/.

You are to deliver code that prices a supermarket shopping basket. Some items available are based on price per item, some items are based on weight. There are also group discounts to be aware of:

- Three cans of beans for the price of two.
- Two cans of Coke, for £1.


Use the following example of a receipt to know what data needs to be captured. There is no requirement to actually format or print a receipt.

    Beans                0.50
    Beans                0.50
    Beans                0.50
    Coke                 0.70
    Coke                 0.70
    Oranges
    0.200 kg @  £1.99/kg 0.40
                        -----
    Sub-total            3.30

    Savings
    Beans 3 for 2       -0.50
    Coke 2 for £1       -0.40
                        -----
    Total savings       -0.90
    -------------------------
    Total to Pay         2.40


**Keep it simple and to the point, no web, persistence, ORM layers or frameworks.** 

**Don't try and invent complex money classes, but don't fall for classic Java Money issues.**

**What we want to see is what classes you create, their responsibility and relationships with other classes.**

1. Think how to make pricing and discounts flexible
2. Think about immutability
3. Apply S.O.L.I.D principles. https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)
4. Show us how you write clean code. 

**We will run your code over our static analysis tool, so make sure it doesn't have any issues!**

You can use TDD, or BDD, or just good selective test coverage. It is very important to write `tests` that help us understand your design; what you think are the important business rules that are to be protected when changes come later.

## How to proceed
1. Create a github account if you don't already have one. (it’s free)
2. Create a new project with README explaining what the project is doing, and how to run from the command line
3. Use Maven as your build tool
4. Add dominicfarr and iggymoran as a contributors
5. Commit often, so we can see how you grow your code. 
6. When you are finished create a pull request for us to start the code review process. 

We don’t put any time frame on the completion, but the sooner you complete, the sooner we can move forward in the hiring process, and, we hope, sooner we can make an offer to you. 

If you have any questions at all please contact [dfarr@policyexpert.co.uk](mailTo:dfarr@policyexpert.co.uk) and [jruckwood@policyexpert.co.uk](mailTo:jruckwood@policyexpert.co.uk) and we will be happy to help.

Enjoy!
