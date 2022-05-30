# markdown-practice
Explore the "Jobs" tab in LinkedIn web application.

# Test Plan Example
##### Author: Mennatullah Alaa
##### Version: V1
***

## About LinkedIn Web Application 

### What the LinkedIN is:

A LinkedIn is the world's largest professional network on the internet. You can use LinkedIn to find the right job or internship, connect and strengthen professional relationships, and learn the skills you need to succeed in your career.


### Who will use the website?

LinkedIn is a platform for anyone who is looking to advance their career. This can include people from various professional backgrounds, such as small business owners, students, and job seekers.


### What is it used for?

Connect the world’s professionals to make them more productive and successful.

### How will it work?
1. Create your profile: Signing up and creating your profile is the best way to begin using LinkedIn. Through your profile, you can showcase your professional life, milestones, skills and interests.

2. Build your network: You can begin by adding your family, friends, past or current classmates, and coworkers to your network. You can also follow people, companies, or topics by navigating directly to the Follow fresh perspectives page.

3. Find a job: If you’re looking for a new professional opportunity, you can get started on your job search on LinkedIn. You can use LinkedIn to research companies and reach out to the hiring community. You can also apply directly for roles, save job searches, and notify your connections and recruiters that you’re open for job opportunities.


### What are software the product uses?

 * Supported browsers: Chrome, FireFox, Safari & Edge. With following URL :  [LinkedIN](https://www.linkedin.com/ ) .
 * Supported OS : Windows, Linux and Mac OS. 
 
***


## Testing Strategy

### Testing Scope:
Jobs feature With following URL :  [Jobs service](https://www.linkedin.com/jobs ) .

* Type of users:
	* Job seeker.
	* Job creator.

* In-scope items: 
	* Functional Testing.
	* Api Testing.
	* Usability Testing.

* Out of scope items: 
	* Database Testing
	* Hardware & any other external interfaces.

### Test Levels:

* Unit Testing: Done by developer.
* API Testing:
	* unit testing on the code level : Done by developers.
	* finctional testing on web service layer: Done by Testers.
* Integration Testing:  Done by Testers.
* System Testing:  Done by Testers and Product owners.

***

### Risk Analysis and Mitigation:

Risk is future’s `uncertain` event with a `probability of occurrence` and a `potential for loss`. When the risk actually happens, it becomes the `issue`.


| Risk	        | Mitigation  | 
| ------------- |-------------| 
| Team member lack the required skills for website testing.| Plan training course to skill up your members |
| The project schedule is too tight; it’s hard to complete this project on time     | Set Test Priority for each of the test activity.      |
| A lack of cooperation negatively affects your employees productivity|Encourage each team member in his task, and inspire them to greater efforts.|

### Test Objective:

1. Check that jobs feature `functionality` is working as expected without any error or bugs in real business environment.

2. Check that the user interface `UI` is displaying as expected and & meet the customer needs.

3. Verify the `usability` of the web application. Are those functionalities convenient for user or not? , user friendly or not?

### Test Criteria:
* Suspension criteria:
	* if 40% of test cases failed, the test should be suspended until the development team fixes all the failed cases.

* Exit criteria: 
	* Run rate is mandatory to be 100% unless a clear reason is given.
	* Pass rate should be at least (80%), with 0 critical or major issues. not more 10 minor issues.
	
	
### Test Estimates:

* Break out the whole project into small tasks and add the estimation for each task.	
* The working days, the project deadline, resource availability should be taken into consideration while setting the test estimates.


### Test System Resources:

1. Test tool: The testing tool is to automate the testing, simulate the user operation, generate the test results as:
	* Selenium web driver.
	* RestAssured.
	* TestNG.
	* Extent Report.

2. Network: need a Network include Internet to simulate the real business and user environment.

3. Platforms: The target operating systems which users often use to connect the internet:
	* Windows.
	* Linux.
	* Mac.

4. Browsers: The environment that web application will run on:
	* Chrome
	* FireFox
	* Safari 
	* Edge
	


### Test Deliverables:
Test Deliverables:  is a list of all the documents, tools and other components that has to be developed and maintained in support of the testing effort.

1. Test deliverables are provided `before` testing phase:
	* Test plans document.
	* Test cases documents.
	* Test Design specifications.
	
2. Test deliverables are provided `during` the testing:
	* Test Scripts.
	* Simulators.
	* Test Data.
	* Error logs and execution logs.
	
3. Test deliverables are provided `after` the testing cycles is over:
	* Test Results/reports.
	* Defect Report.
	* Release notes.


*** 





## Test Focus Areas According to Their Business Impact:

#### Pre-Conditions:
* Create a LinkedIn Account and Add a Photo.
* Build a LinkedIn Profile That Attracts Employers.
	* List a Summary about you including experience, skills, and interests.
	* List your current and past jobs, certifications you’ve earned. 
* Build Your LinkedIn Network.

	
#### Test Scenarios To Be Covered:
1. For Job `Seeker` :

	* UI of Jobs landing page shall be as designed and user friendly.
	* User can easily search for jobs on LinkedIn from the Jobs homepage.
	* User can upload his/her resume from the Job Application Settings page by clicking Upload under the Resume section. 
	* User can easily apply for job on LinkedIn. Based on what the job poster chooses, user'll see an Easy Apply/Apply Now or Apply button.
	* User can Save jobs while browsing job search results on LinkedIn to come back later to apply for them.
	* User can set up job alerts based on his/her previous job searches, preferences, and specific companies to ensure he/she will regularly receive relevant job notifications.
	* User can narrow down his/her job search results using filters, keywords, and advanced search.
	* User be able to reuse uploaded resume for future job applications.



2. For Job `Creator`:
	* User can write a detailed job description that includes the required skills to target job seekers who match his/her criteria. 
	* User can view his/her published job post by clicking Manage job posts from the Jobs homepage.
	* User can Edit the job post.
	* User can share the job post with his/her LinkedIn network.
	* User can review job applicants. View their profile, resume (if provided) directly from the application.
	* User can rate applicants as Good fit, Maybe, or Not a Fit.
	* Once user has found a good fit for his/her role,  User can close the job post and can repost the job at any time.
	* User can message applicants directly from the Applicants page of his/her job post.
	* User can set up automatic ratings and rejection messages to automate his/her hiring workflow.























