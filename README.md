# Problem Statement
The number of couples who call it quits after a year or so is staggering. Among differences in opinion, life styles and other aspects, financial stress is one of the leading causes of breakups. In fact, experiencing money troubles is the 8th reason why couples break up (or divorce) in the US. At Intuit, we want to help couples stay together. The following exercise is aimed at coming up with a solution to help current or future couples stay together.
To help our cause, we are providing you with a 2-year list of Mint transaction data from individuals who could likely be dating. We would like to increase the likelihood of people who have broken up (or were recently divorced) to have more successful current or future relationships.

# The Data
You will be provided with Mint financial transaction data is in CSV format with the columns:
```
auth_id |    Date      |    Vendor Description   |    Amount   |   Location
112341    1/23/2013        Restaurant - Pizza        18.74           CA
```

# Your Task:
Your task is to identify features – details about the individual and their life styles, among any other information you can extract from their transaction data, that might help people engage in longer lasting relationships. For instance, you might find that someone is a student (you can encode that in a binary fashion – yes/no or 1/0). Note that each transaction belongs to a unique individual who is associated with an ‘auth ID’. Furthermore, you will need to:

1. Parse the data and create a new table that includes a wide range of distinct details (or features) that you have inferred about each individual from the data set. For example, what their income is, what their hobbies might be, if the person had a child or not
2. BONUS: Using the distinct features you inferred, provide a score between 0-1 to measure of compatibility between any two individuals, with all rationale behind the score explained in your README
 
# Requirements:
* Create a solution that uses the Mint transaction data to infer certain details or features about any given individual
* The solution can be a graphical tool, an API, or a CLI tool
* Only one student is allowed per submission, you cannot work in teams
* Your solution must run or compile
* In your README, please include a write up of the rationale that you used to infer distinct details or features about each individual.
* For the BONUS problem, please include a write up of the rationale you used to determine the measure by which you determined people’s compatibility
 
# Submission:
* Submit your solution by uploading it to GitHub and emailing us a link to your repository at intuitatrit@gmail.com
* Provide a README with detailed instructions on installing and running your solution. "Download and run" is not sufficient instructions, assume the grader is not experienced with the language or tooling you've used.
 
# Disclaimer:
This is merely an exercise to test your thinking about a problem that we are passionate about. It is not intended to create any stereotypes or make relevant suggestions regarding relationships. Please take all learnings from this problem with a grain of salt.