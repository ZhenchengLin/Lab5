# Lab report 5
## Scenario 1
<img width="611" alt="image" src="https://github.com/ZhenchengLin/Lab5/assets/130115215/f0b876f1-bcb0-450a-ad08-739162e2332d"> 

## Part-1
#### Question 1
**What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?**
On macbook, using VScode.
#### Question 2
**Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.**
When I run Junit with the ArrayTest.java file it just shown this
<img width="953" alt="image" src="https://github.com/ZhenchengLin/Lab5/assets/130115215/76833689-b7e5-43ad-afa9-4cee2f424f35">  
It says it fail says file not found.
I was expected to see 2 test passed.

#### Question 3
**Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.**
When I trying to use terminal to run my file ArrayTests.java class.
The input I put in is `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests.java`

### 1. "TA" respons
Check the input file. Should it contain .java at the end?
### 2. "TRYING" fixing it
I remove `.java` at the end when it works!!
<img width="935" alt="image" src="https://github.com/ZhenchengLin/Lab5/assets/130115215/c308163d-ae20-48bd-a060-bda3890329e6">
### 3.
I have git clone the need files in to my ieng6 remote server. 
<img width="935" alt="image" src="https://github.com/ZhenchengLin/Lab5/assets/130115215/642fda19-cf2e-4c74-87d8-a655bc340ed8">
Then I set it up the same as the Scenario by adding `.java` at the end of this `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests`

The full code that trigger this bug is `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ArrayTests.java`

We use have to remove the `.java` at the end 

## Part-2
I think 15L is a course that is much more important while dealing with skills on coding. This course help a lot to understanding where are all the files are runing. In the same time we learn to use differnt fasting ways to code, also learn a lots form git. 

