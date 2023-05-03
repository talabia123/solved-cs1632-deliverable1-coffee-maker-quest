Download Link: https://assignmentchef.com/product/solved-cs1632-deliverable1-coffee-maker-quest
<br>
For this assignment, your group will determine a test plan for the simple gameCoffee Maker Quest, based on the requirements listed. There are several knowndefects in the software; you will need to find and report on at least three.Additionally, a traceability matrix showing the mapping of test cases torequirements is required.

There should be two and only two members in a group. You may choose to work onthe assignment alone if that’s what you prefer.

There should be at least one test case per requirement, although I wouldnormally expect several test cases per requirement.

Each requirement should have AT LEAST one test case associated with it in orderto have good test coverage. Each test case should have AT LEAST onerequirement associated with it (no orphaned test cases). One test case mayhappen to test more than one requirement using a single set of inputs, and thatis fine. The above can easily be checked via a traceability matrix (which youshould also deliver).

Test cases should mention all necessary preconditions, execution steps, and postconditions.

I expect you to test several edge and corner cases as part of the test plan.If you do this, I’d estimate that the number of test cases is at least 2x thenumber of requirements. If the number of test cases is more than 3x the numberof requirements, you are probably overtesting.

You are expected to execute the test plan in order to find the defects. Thereare AT LEAST three. Full credit will be given only to those who properly findand describe at least three. While you are not expected to find all of thedefects, a reasonable test plan should definitely find at least three. This isan intentionally target-rich environment.

## FormatThe report should start with a cover page with:* The name of the project under test* The names of the people in the group* The title “CS 1632 – DELIVERABLE 1: Test Plan and Traceability Matrix”

There should be a short introduction (a few paragraphs) in which you may noteany concerns or difficulties you may have had or anticipate with the testingprocess. You should also note why you considered certain test cases, how youcame up with edge cases, etc.

ON A NEW PAGE, a traceability matrix should be provided mapping the test caseswith their associated requirements. Remember that all requirements should mapto AT LEAST ONE test case, and all test cases should map to AT LEAST ONErequirement.

ON A NEW PAGE, a list of the actual test cases should follow. You may namethem any way you wish, but please be consistent. Please write them out in thisformat –

IDENTIFIER:TEST CASE:PRECONDITIONS:EXECUTION STEPS:POSTCONDITIONS:

ON A NEW PAGE, list at least three defects found. The defects should followthe defect reporting template:

IDENTIFIER:SUMMARY:DESCRIPTION:REPRODUCTION STEPS:EXPECTED BEHAVIOR:OBSERVED BEHAVIOR:

Please apply all the things you learned through **Exercise 1** to thisdeliverable. For example, don’t forget to include any preconditions at thebeginning of the REPRODUCTION STEPS.

There are a few things that are different from Exercise 1 though:

1. Execution Steps: Exercise 1 had just one execution step (launching theprogram). You will have multiple steps for most test cases in thisdeliverable. All steps must numbered and clearly delineated. It should notsay “Go north”. Instead it should say “Type N and press [Enter]”.

2. Preconditions: Unlike Exercise 1, now preconditions can include programstate as well as other system state. For example, you might want express aprecondition that the player has sugar in possession. Now you have twooptions: 1) Just straight up say “The player has sugar” or 2) List the inputsteps that led to the program state where the player has sugar. Which do youprefer?

The former has brevity on its side, but if you really want your test case tobe reproducible you should really do the latter. Because depending on thesteps you took the acquire the sugar, the program could be internally in adifferent state. For example, suppose the program has an internal counter thatcounts the number of rooms visited by the player. Depending on the route youtook to get to the sugar, that counter value would be different and that valuemay impact the final outcome of your program!

So in summary, always describe preconditions as a series of performedactions rather than the external visible program state. This also applies todefect reporting. Then you may ask, wouldn’t that make the preconditionsharder to read? It’s much easier to understand “the player has sugar” ratherthan trying to decypher the series of steps that leads to that precondition.Well, you can describe the preconditions you are trying to achieve at thebeginning of the PRECONDITIONS item and then list the steps that get you there.Phew!

## Coffee Maker Quest

Coffee Maker Quest is a simple game. The goal is get coffee, sugar, and cream,and then drink it so that you can stay up and study. In order to do so, youneed to visit several rooms in a house and look around. Once you have obtainedall the necessary elements, you win. If you decide to drink before getting allof the necessary elements, you lose.

You can run it downloading the coffeemaker.jar file and running:“`bashjava -jar coffeemaker.jar“`

The requirements are listed in the file [requirements.txt](requirements.txt).

## Tips

Please read [deliverable1-tips.md](deliverable1-tips.md) if you are confused.

## Grading* Introduction: 10% of grade* Test Plan: 40% of grade* Traceability Matrix: 20% of grade* Defects Found and Described: 30% of grade

Please review the [grading_rubric.txt](grading_rubric.txt) for details.

## Submission

Please use the [ReportTemplate.docx](ReportTemplate.docx) file provided in thisdirectory to write your report. If you don’t have a .docx compatible word processor,that’s perfectly fine as long as you follow the same organization. A PDF version ofthe file is at [ReportTemplate.pdf](ReportTemplate.pdf). Please make sure thatthe intro, traceability matrix, test cases, and defects are on seperate pages. You willbe submitting to GradeScope in PDF format. When you submit, you will be askedto assign pages in the PDF file to each rubric item: 1. Introduction, 2.Traceability Matrix, 3. Test Cases, and 4. Defects.

Each pairwise group will submit the exercise *once* to GradeScope, by *onemember* of the group. The submitting member will press the “View or editgroup” link at the top-right corner of the assignment page before or aftersubmission to add his/her partner. Make sure that your partner is there, orhe/she will not get a grade.