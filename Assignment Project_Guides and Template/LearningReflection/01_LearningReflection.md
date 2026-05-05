
# TODO

> Please use the below questions as guidelines to help you think and plan your Learning Reflection Report

## 1. How was your experience testing the given Webapp?

Testing the web application was practical and insightful. It helped me understand how real-world applications behave under different user inputs. I found it interesting to explore different scenarios, especially identifying edge cases and validation errors. It also made me realize how important it is to think from a user's perspective while testing.
     
## 2. How did you write or manage your test case? Describe the process.

I followed the template that was given to us and used the LoginPage as a reference example.
1. Exploring the pages first: I navigated to each page (Register, Project, Issue) to understand the inputs, workflows, and error states.
2. Defining variables: I listed all test data upfront in the variables section so that test steps reference variable names rather than hardcoded values. This makes tests easier to maintain.
3. Writing positive tests first: I started with the good scenarios.
4. Writing negative tests: I thought about what could go wrong: empty fields, duplicate data, invalid formats or missing required steps.

## 3. Do you recommend any other tools or styles for Test case management. 
  
Yes, I would recommend tools like Jira with Zephyr or TestRail for managing test cases in a more professional environment. These tools help organize test cases, track execution, and link them with bug reports. For style, using BDD with Gherkin can make test cases more readable and understandable for both technical and non-technical team members.

## 4. Which IDE (Visual Code or Atom or else) have you used to edit files?

I used Visual Studio Code to edit all files in this assignment.
     
## 5. Did you find any trouble? how did you solve the trouble?

Yes, initially I had some difficulty understanding how detailed the test steps should be and how to properly define expected results. I solved this by reviewing the example template and thinking from a real user perspective. 

## 6. Did you find any trouble using Github? have you used Github before? where?
 
GitHub itself was straightforward to use for this assignment. I have used GitHub previously in other assigments and personal projects, so I was comfortable with creating a repository and adding files. 

## 7. If in the future if you need to automate these test cases, which framework or language will you use? and describe why (Robot Framework, Cypress, Selenium, or any other )

I would choose Cypress with JavaScript for automating these test cases. Cypress provides built-in waiting, clear error messages, and a good user interface for debugging tests. Since many web applications use JavaScript, it is also practical to use the same language for testing.

## 8. Kindly search the term `Tester` `Automation Tester` glassdoor and LinkedIn or any other job search website. Currently, list the skills and competencies that are most in-demand in software testing

Based on a search of current job offerings for software testing roles, the most commonly required skills and competencies include:
Technical Skills:
- Automation frameworks: Selenium, Cypress, Playwright, Robot Framework
- Programming languages: Python, JavaScript, Java
- API testing tools: Postman, REST Assured
- CI/CD integration: Jenkins, GitHub Actions, GitLab CI
- Test management tools: Jira, TestRail, Zephyr
- Performance testing: JMeter, k6
- Version control: Git / GitHub / GitLab
- BDD/TDD methodologies and Gherkin/Cucumber

Other Skills:
- Analytical thinking and attention to detail
- Clear written and verbal communication
- Collaboration with developers and product owners
- Problem-solving mindset
- Ability to work in Agile/Scrum teams

## 9. **Let's assume** that if you are going to continue with the career in Software Testing, which technical and soft skills do you need to fill up the blank in your resume?

Based on the research above and my current skill set, I would need to develop:
- Hands-on experience with at least one automation framework
- Setting up and running tests in a CI/CD pipeline
- Performance testing basics with a tool like JMeter
- Writing clearer and more concise bug reports 
- Communicating test results to non-technical stakeholders
- Time management when working under sprint deadlines in an Agile team

## 10. Write short Learning Reflection and  Free words Do you think that project helped in putting theoretical knowledge into practice? Describe? (is there anything else that you would like to share with us concerning the current study module). e.g. regarding the quality of content and your learning (or) improvement ideas? 

This project definitely helped me put theoretical knowledge into practice. Before this, I understood testing concepts mainly in theory, but this assignment showed me how to apply them in a real application. 
It improved my ability to think critically, design structured test cases, and identify possible issues in a system. I also gained a better understanding of how testers contribute to software quality.
One improvement suggestion would be to include more real-world examples or a short demo of the application workflow before starting the assignment. This would make it easier to understand the system faster.
Overall, this module was very useful and gave me practical skills that I can use in future projects and potentially in a professional testing role.
