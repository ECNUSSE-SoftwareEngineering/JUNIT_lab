## Assignment 1: Design Line/Branch Tests
Learn to use JUnit in IDE (Android Studio / IDEA / VS Code). Design JUnit test cases for the function `Triang` in the original file **Tritype.java**. Improve line/statement coverage and branch/decision/edge coverage as much as possible.

1. Learn to use JUnit in IDE (Android Studio / IDEA / VS Code)

|IDE|Tutorial|
|:-:|:-:|
|IntelliJ IDEA|[How to use JUnit4 in IntelliJ IDEA ](https://www.yuque.com/yiheng-dirap/vkgmh9/vmfblz?)|
|Android Studio|[How to use Junit4 in Android Studio ](https://sy8pzmhmun.feishu.cn/docx/R2o7dRSCSo4u74x1xuCcZ5IOnke)|
|VS Code|[How to use JUnit4 in VSCode ](https://sy8pzmhmun.feishu.cn/wiki/IETkwrTyIi1lH8kL1zzcoulxnA7)|

2. Create a new project in the selected IDE and copy the file **Tritype.java** into the project.
3. Create a test class named `TritypeLineBranchTest` and write JUnit test cases within it to ensure that line and branch coverage are as high as possible, while ensuring all JUnit test cases run successfully.
4. Obtain a screenshot of the Jacoco coverage report and name it **line_branch_coverage.png**. Upload the `TritypeLineBranchTest` test class file and the coverage report screenshot to the root directory of the repository.

## Assignment 2: Design Logical Coverage Tests

Choose a decision that contains at least two conditions and design test cases for it to meet: decision coverage, condition coverage, and MC/DC coverage.

0. Create a new project in the selected IDE and copy the file **Tritype.java** into the project.
1. Choose a decision that contains at least two conditions.
2. Create three test classes: `TritypeDecisionTest`, `TritypeConditionTest`, and `TritypeMCDCTest`. In each corresponding test class, design JUnit test cases that satisfy decision, condition, or MC/DC coverage for the selected decision statement, ensuring all JUnit test cases run successfully.
3. Add comments to each of the three test classes indicating which coverage is being tested.
4. Upload these test class files to the root directory of the repository.


## Assignment 3: Design Mutation-based Tests
For the two given mutant programs (i.e., **TritypeMutantOne.java** and **TritypeMutantTwo.java**), design two test cases to kill each of these mutants respectively.

1. Import the mutant files (**TritypeMutantOne.java** and **TritypeMutantTwo.java**) into your project.
2. Create a test class named `TritypeMutationTest` and write two JUnit test cases within it to "kill" the two mutants, ensuring all JUnit test cases run successfully.
3. Upload the `TritypeMutationTest` test class file to the root directory of the repository.

## Submission
After you've completed all three assignments, there should be five test class files (**TritypeLineBranchTest.java**, **TritypeConditionTest.java**, **TritypeDecisionTest.java**, **TritypeMCDCTest.java**, **Tritype MutationTest.java**) and a coverage report screenshot **line_branch_coverage.png**.
