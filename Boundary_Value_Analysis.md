# Boundary Value Analysis Exercise

## Introduction
Welcome back, testing enthusiasts! In our previous exercise, we explored the world of equivalence partitioning and how it helps us design effective test cases. Now, we're going to level up our testing game with boundary value analysis! 🚀

Boundary value analysis is like the close cousin of equivalence partitioning. While equivalence partitioning focuses on representative values from each equivalence class, boundary value analysis zooms in on the values at the edges of those classes. It's all about pushing the boundaries (pun intended) and making sure our system can handle those tricky edge cases.

Think of it like a game of "The Floor is Lava" 🌋. Just like how you carefully test the boundaries of each safe zone, boundary value analysis helps us test the limits of our input domains. We want to make sure our system doesn't fall into the lava of unexpected behavior! 😄

## Why is Boundary Value Analysis Important?

Now, you might be wondering, "Why should I care about boundary values? Aren't they just special cases?" Well, let me tell you, boundary value analysis is like the secret sauce of testing! 🍝

1. 🐛 **Defect Detection**: Many defects tend to lurk around the boundaries of input domains. By focusing on these values, we increase our chances of uncovering those sneaky bugs!

2. 🌈 **Edge Case Coverage**: Boundary value analysis helps us cover the edge cases that might be missed by other testing techniques. It ensures that our system can handle those unique and extreme scenarios.

3. 🎯 **Robustness Testing**: By testing the boundary values, we can assess the robustness of our system. We want to make sure it doesn't crumble under pressure and can gracefully handle those borderline cases.

4. 📊 **Complementing Equivalence Partitioning**: Boundary value analysis perfectly complements equivalence partitioning. It adds an extra layer of thoroughness to our testing approach, making sure we don't miss any critical scenarios.

## Boundary Value Analysis in Action

Alright, let's put boundary value analysis into practice! In this exercise, we'll tackle a scenario where you'll identify boundary values and design test cases to cover them. Get ready to push those boundaries and uncover any lurking defects! 💪

## Objective
In this exercise, you will practice applying the boundary value analysis technique to identify boundary values and design test cases for a search functionality with a numeric input field.

## Scenario
You are tasked with testing a search functionality that allows users to specify the number of results per page. The valid range for the number of results per page is between 1 and 100 (inclusive).

## Instructions

### Task 1: Identify Boundary Values
1. Identify the boundary values for the numeric input field.
2. Consider both valid and invalid boundary values.
3. Fill in the table below with the identified boundary values.

| Boundary Values |
|-----------------|
|                 |
|                 |
|                 |
|                 |
|                 |

### Task 2: Design Test Cases
1. Design test cases to cover the identified boundary values.
2. Ensure that your test cases cover both valid and invalid scenarios.
3. Fill in the table below with the designed test cases.

| Test Case | Input Value | Expected Result |
|-----------|-------------|-----------------|
|           |             |                 |
|           |             |                 |
|           |             |                 |
|           |             |                 |
|           |             |                 |

### Task 3: Discuss and Share
1. Discuss your boundary values and test cases with your group.
2. Be prepared to share your approach and findings with the class.

## Considerations
- Think about the edge cases and how to test them effectively.
- Consider both valid and invalid boundary values.
- Remember that boundary value analysis helps in identifying defects that may occur at the boundaries of the input domain.

<details>
  <summary>Model Answers</summary>

### Task 1: Identify Boundary Values
| Boundary Values |
|-----------------|
| 0               |
| 1               |
| 2               |
| 99              |
| 100             |
| 101             |
| -1              |
| Non-numeric     |

### Task 2: Design Test Cases
| Test Case | Input Value | Expected Result |
|-----------|-------------|-----------------|
| TC1       | 0           | Error message   |
| TC2       | 1           | Valid, displays 1 result per page |
| TC3       | 2           | Valid, displays 2 results per page |
| TC4       | 99          | Valid, displays 99 results per page |
| TC5       | 100         | Valid, displays 100 results per page |
| TC6       | 101         | Error message   |
| TC7       | -1          | Error message   |
| TC8       | "abc"       | Error message   |

</details>

By applying boundary value analysis, you'll be able to design test cases that cover the critical boundary values and uncover any defects hiding at the edges. Remember, pushing the boundaries is what makes testing exciting and effective! 🌟

Happy boundary testing! 🎉
