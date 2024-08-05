# Decision Table Testing Exercise

## Introduction
Hello, my fellow testing adventurers! 🧭 In our previous exercises, we explored the realms of equivalence partitioning and boundary value analysis. Today, we embark on a new quest: decision table testing! 🗺️

Decision table testing is like a treasure map that guides us through the complex labyrinth of conditions and actions. It helps us navigate the various combinations of inputs and their corresponding outputs, ensuring that our system behaves as expected.

It's like having a cheat sheet that tells us, "If these conditions are met, then these actions should be taken." 😎

## Why Use Decision Table Testing?

Now, you might be thinking, "Decision tables sound fancy, but why should I bother with them?" Well, decision table testing is like a secret weapon in your testing arsenal! 🗡️

1. 🌿 **Clarity and Organization**: Decision tables provide a clear and organized way to represent complex business rules and logic. They help us understand the relationships between conditions and actions, making it easier to design comprehensive test cases.

2. 🔍 **Completeness and Coverage**: By creating a decision table, we can ensure that we cover all possible combinations of conditions. No scenario will slip through the cracks, and we'll have a complete set of test cases.

3. 🤝 **Communication and Collaboration**: Decision tables serve as a great communication tool between testers, developers, and business stakeholders. They provide a visual representation of the system's behavior, making it easier for everyone to understand and agree upon the expected outcomes.

4. 🎯 **Defect Detection**: Decision table testing helps us identify defects that may arise from incorrect or missing combinations of conditions. By testing all the different scenarios, we can uncover bugs and ensure the system handles each case correctly.

## Example of Decision Tables

Let's walk through an example of a decision table to help you understand the concept better. We'll use a simple scenario of a library's book borrowing policy. 📚

Imagine a library has the following rules for borrowing books:
- If the borrower is a student and the book is available, they can borrow the book.
- If the borrower is a teacher, they can borrow the book regardless of its availability.
- If the borrower is neither a student nor a teacher, they can only borrow the book if it's available and they pay a fee.

Now, let's create a decision table to represent these rules:

| Conditions | Test Case 1 | Test Case 2 | Test Case 3 | Test Case 4 | Test Case 5 | Test Case 6 |
|------------|-------------|-------------|-------------|-------------|-------------|-------------|
| Borrower Type | Student | Student | Teacher | Teacher | Other | Other |
| Book Availability | Available | Not Available | Available | Not Available | Available | Not Available |
| Allow Borrowing | ✓ | ✗ | ✓ | ✓ | ✓ | ✗ |
| Charge Fee | ✗ | ✗ | ✗ | ✗ | ✓ | ✗ |

Let's break down the decision table:

1. **Conditions**: The decision table starts with the conditions that affect the outcome. In this case, we have two conditions: "Borrower Type" and "Book Availability." The possible values for each condition are listed in the corresponding columns.

2. **Actions**: Below the conditions, we have the actions or outcomes that result from different combinations of the conditions. In this example, the actions are "Allow Borrowing" and "Charge Fee."

3. **Condition Combinations**: Each column in the decision table represents a different combination of the condition values. For example, the first column represents the combination of a student borrower and an available book.

4. **Action Outcomes**: The cells under each action indicate the outcome for that particular combination of conditions. A checkmark (✓) means the action is performed, while a cross (✗) means the action is not performed.

Now, let's interpret the decision table:
- If the borrower is a student and the book is available, they are allowed to borrow the book without being charged a fee.
- If the borrower is a student but the book is not available, they are not allowed to borrow the book.
- If the borrower is a teacher, they are allowed to borrow the book regardless of its availability, and they are not charged a fee.
- If the borrower is neither a student nor a teacher (categorized as "Other") and the book is available, they are allowed to borrow the book but are charged a fee.
- If the borrower is neither a student nor a teacher and the book is not available, they are not allowed to borrow the book.

As you can see, the decision table provides a clear and concise way to represent the different scenarios and their corresponding outcomes. It helps in understanding the logic behind the system's behavior and ensures that all possible combinations of conditions are considered.

When creating a decision table, follow these steps:
1. Identify the conditions that affect the outcome and list them in the table.
2. Identify the possible values for each condition and list them in the corresponding columns.
3. Identify the actions or outcomes and list them below the conditions.
4. Fill in the cells under each action with the appropriate outcome (e.g., checkmark or cross) for each combination of conditions.
5. Verify that all possible combinations of conditions are covered in the decision table.

By following these steps, you'll be able to create a decision table that accurately represents the logic and behavior of the system you're testing.

Remember, decision tables are a powerful tool for organizing and visualizing complex business rules and logic. They help in designing comprehensive test cases and ensuring that all scenarios are considered.

I hope this example and explanation have clarified the concept of decision tables for you. Let me know if you have any further questions!

## Let's Create a Decision Table!

Alright, now it's time to roll up our sleeves and create a decision table! In this exercise, we'll tackle a shopping cart functionality that behaves differently based on various conditions. Get ready to unleash your inner decision table wizard! 🧙‍♂️

## Objective
In this exercise, you will practice applying the decision table testing technique to create a decision table for a shopping cart functionality with different combinations of product types, quantities, and discount codes.

## Scenario
You are tasked with testing a shopping cart functionality that behaves differently based on the following conditions:
- Product Type: The product can be either physical or digital.
- Quantity: The quantity of the product can be 1 or 2.
- Discount Code: The discount code can be either valid or invalid.

The shopping cart system performs the following actions based on the combinations of the above conditions:
- Calculate Subtotal: Always calculated.
- Apply Discount: Applied only if the discount code is valid.
- Calculate Tax: Calculated only for physical products.
- Calculate Shipping: Calculated only for physical products.
- Calculate Total: Always calculated.
- Update Inventory: Updated only for physical products.
- Generate Invoice: Always generated.

## Instructions

### Task 1: Identify Conditions and Actions
1. List the conditions and their possible values.
2. List the actions performed by the shopping cart system.

### Task 2: Create the Decision Table
1. Create a decision table with the identified conditions and actions.
2. Fill in the table with the appropriate values for each combination of conditions.
3. Ensure that all possible combinations are covered.

| Conditions | Test Case 1 |
|------------|---------|
| Product Type |       |
| Quantity   |         |
| Discount Code |      |
| Calculate Subtotal |   |
| Apply Discount |      |
| Calculate Tax |       |
| Calculate Shipping |  |
| Calculate Total |     |
| Update Inventory |    |
| Generate Invoice |    |

### Task 3: Identify Test Cases
1. Based on the decision table, identify the test cases that need to be executed.
2. Assign a unique identifier to each test case.
3. Describe the purpose and expected outcome of each test case.

### Task 4: Discuss and Share
1. Discuss your decision table and test cases with your group.
2. Be prepared to present your findings to the class.

## Considerations
- Ensure that all possible combinations of conditions are considered.
- Think about the expected behavior of the system for each combination.
- Consider any additional scenarios or edge cases that may not be covered by the decision table.

<details>
  <summary>Click here to reveal some possible answers</summary>

### Task 1: Identify Conditions and Actions
Conditions:
- Product Type: Physical, Digital
- Quantity: 1, 2
- Discount Code: Valid, Invalid

Actions:
- Calculate Subtotal
- Apply Discount
- Calculate Tax
- Calculate Shipping
- Calculate Total
- Update Inventory
- Generate Invoice

### Task 2: Create the Decision Table
| Conditions | Test Case 1 | Test Case 2 | Test Case 3 | Test Case 4 |
|------------|-------------|-------------|-------------|-------------|
| Product Type | Physical  | Physical    | Digital     | Digital     |
| Quantity   | 1           | 2           | 1           | 2           |
| Discount Code | Valid     | Invalid     | Valid       | Invalid     |
| Actions    |             |             |             |             |
| Calculate Subtotal | ✓   | ✓           | ✓           | ✓           |
| Apply Discount | ✓       | ✗           | ✓           | ✗           |
| Calculate Tax | ✓         | ✓           | ✗           | ✗           |
| Calculate Shipping | ✓   | ✓           | ✗           | ✗           |
| Calculate Total | ✓       | ✓           | ✓           | ✓           |
| Update Inventory | ✓      | ✓           | ✗           | ✗           |
| Generate Invoice | ✓      | ✓           | ✓           | ✓           |

### Task 3: Identify Test Cases
- TC1: Physical product, quantity 1, valid discount code
  - Purpose: Verify the behavior of the system for a physical product with a valid discount code
  - Expected Outcome: Subtotal, discount, tax, shipping, total calculated; inventory updated; invoice generated

- TC2: Physical product, quantity 2, invalid discount code
  - Purpose: Verify the behavior of the system for a physical product with an invalid discount code
  - Expected Outcome: Subtotal, tax, shipping, total calculated; inventory updated; invoice generated; no discount applied

- TC3: Digital product, quantity 1, valid discount code
  - Purpose: Verify the behavior of the system for a digital product with a valid discount code
  - Expected Outcome: Subtotal, discount, total calculated; invoice generated; no tax or shipping calculated; inventory not updated

- TC4: Digital product, quantity 2, invalid discount code
  - Purpose: Verify the behavior of the system for a digital product with an invalid discount code
  - Expected Outcome: Subtotal, total calculated; invoice generated; no discount, tax, or shipping calculated; inventory not updated
 
</details>

By creating a decision table and identifying the test cases, you'll have a clear roadmap for testing the shopping cart functionality. You'll be able to cover all the different scenarios and ensure that the system behaves correctly under various conditions.

Remember, decision tables are your friends! They help you navigate the complex world of conditions and actions, ensuring that no combination is left untested. 🌍

Happy decision table testing! 🎉
