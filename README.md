# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

Loom Recording Link: [Insert Link]

# Project Overview

In this project, you will be presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. Your task is to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

You will present your reasoning for each example, record your presentation using Loom, and submit your findings along with the Loom recording to the Project Tab on the Learning Management System (LMS).

# Instructions

## Step 1: Clone the Repository

Repo Link: https://github.com/CodeSpace-Academy/Module_3_StudentNo_Classcode_Group_Name-Surname_JSL03

1. Access the provided repository containing the starter code and presentation template.
2. Clone the repository.
3. Open the cloned repository in your preferred code editor.

## Step 2: Analyze the Examples

1. In the cloned repository, you will find two JavaScript code examples labeled "Example 1" and "Example 2."
2. Examine each code example and determine which one follows an imperative programming style and which one follows a declarative programming style.

## Step 3: Record Your Presentation

1. Use Loom (https://www.loom.com/).
2. Create a single video presentation for both examples that include the following:

   - Introduction of the example number.
   - Explanation of whether the example is imperative or declarative.
   - Detailed reasoning for your choice, discussing the code logic and style used in the example.
   - Mention any specific code structures or patterns that align with the chosen programming paradigm.
   
3. Keep each video presentation concise, with a maximum length of 2 minutes for each example. Your total recording time should not exceed 5 minutes.

## Step 4: Insert Loom Links

1. After recording, upload your presentation videos to Loom.
2. Obtain the Loom recording links for the video presentation.
3. Edit the `README.md` file in the cloned repository and insert the Loom recording links.
   
## Step 5: Submit Your Project
1. Commit your changes to the Git repository and push them to your GitHub account.
2. Ensure that the repository is public so that it can be accessed.
3. Submit the GitHub project link (URL) that includes your Loom recording link to the [JSL03] Project Tab on the LMS for evaluation.

# Project Evaluation

Your project will be evaluated based on your ability to:

- Accurately identify and differentiate between imperative and declarative programming styles.
- Provide clear and well-reasoned explanations for your choices.
- Present your findings concisely within the specified time limit.
- Follow the submission instructions accurately.

Follow the steps outlined above to complete the project successfully.

# Presentation Talking Points

Example #: 1

## Imperative Approach [2 Minutes]
1. **Step-by-Step Explanation:** Start by explaining the code logic in the imperative approach.
   - We begin by initializing our grill temperature and steak temperature variables to zero.
   - We preheat the grill to a specific temperature, here set to 204°C.
   - We season the steak with salt and pepper on both sides.
   - We enter a loop where we continuously grill the steak until it reaches the desired level of doneness. Inside the loop, we grill the steak, measure its   internal temperature, adjust grill temperature and cooking time based on steak weight and desired doneness, and update the steak temperature accordingly.
   - Once the steak reaches the desired doneness, we exit the loop.
   - We serve the steak. If the steak's temperature is at or above the desired doneness, we return "Steak is ready to serve!" Otherwise, we return "Steak needs more cooking."
2. **Emphasis on How:** Highlight how the imperative approach focuses on detailing "how" the task is accomplished.
   - The imperative approach is all about detailing "how" the task is accomplished.
   - We utilize loops, conditions, and explicit instructions to control the cooking process.
   - Mutable variables like grillTemperature, steakTemperature, and seasoning are used to track and update the state and progress of the cooking process.


Example #: 2

## Declarative Approach [2 Minutes]
1. **High-Level Process Description:** Explain the code logic in the declarative approach.
   - In the declarative paradigm, we describe the cooking process in a high-level, abstract manner.
   - The code focuses on defining "what" should happen rather than "how" it should happen.
   We abstract away the implementation details and instead provide a structured overview of the cooking process.
   - For instance, we define steps like preheating the grill, seasoning the steak, cooking until desired doneness, and serving the steak without detailing   the exact actions to perform at each step.
2. **Use of Data Structures:** Discuss the use of data structures (e.g., arrays, objects) to represent the process steps.
   - In our code, we use a data structure—an array of objects—to represent the cooking process.
   - Each object in the array represents a step in the process, containing properties such as action, temperature, and seasoning.
   - This structured format organizes the process steps clearly, making it easy to understand and maintain.
   - Additionally, we use a for...of loop to iterate over these steps and a switch statement to execute the corresponding actions based on the step descriptions.

# Learning Outcome [1 Minute]
- Reflect on what you've learned from analyzing these code examples in different paradigms.

