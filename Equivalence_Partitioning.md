# Equivalence Partitioning Exercise

## Introduction
Hey there, fellow testers! Today, we're diving into the world of equivalence partitioning, a super useful technique in software testing. But before we get our hands dirty with some practical exercises, let's take a moment to understand what equivalence partitioning is all about and why it's such a valuable tool in our testing toolkit.

Imagine you're testing a system that takes various inputs, like age, email, or password. Now, you could go crazy and test every single possible value for each input, but let's be real, that would take forever! 😫 This is where equivalence partitioning comes to the rescue! 🦸‍♀️

Equivalence partitioning is a technique where we divide the input domain (all the possible values) into different classes or sets, called equivalence classes. The idea is that testing one value from each class is enough to catch any defects related to that class. It's like trying out different flavors of ice cream – you don't need to eat the entire tub to know if it's yummy or not! 🍦

Now, you might be thinking, "Why bother with all this equivalence class stuff? Can't I just test random values and call it a day?" Well, hold on there! Equivalence partitioning has some serious benefits:

1. 🎯 **Targeted Testing**: By focusing on representative values from each equivalence class, you can design test cases that are more likely to uncover defects.

2. ⏰ **Time-Saving**: Instead of testing every possible value, you can reduce the number of test cases needed while still maintaining good coverage. That means more time for coffee breaks! ☕

3. 🧩 **Systematic Approach**: Equivalence partitioning provides a structured way to identify test cases, ensuring that you don't miss any important scenarios.

4. 💡 **Clarity and Communication**: When you organize your test cases based on equivalence classes, it becomes easier to understand and communicate the testing approach to your team and stakeholders.

Like any technique, equivalence partitioning has its strengths and limitations. Let's take a quick look at the pros and cons:

✅ Pros:
- Reduces the number of test cases needed
- Helps identify defects related to input handling
- Provides a structured approach to test case design
- Improves test coverage and efficiency

❌ Cons:
- Requires a good understanding of the system's requirements and input domain
- May miss defects that occur due to specific combinations of inputs
- Relies on the tester's judgment in selecting representative values
- May not capture all possible edge cases or boundary values

Alright, now that we've covered the basics, it's time to put equivalence partitioning into action! Roll up your sleeves, grab your favorite testing hat, and let's get started! 🧢✨

## Objective
In this exercise, you will practice applying the equivalence partitioning technique to identify valid and invalid equivalence classes for input fields in a registration form.

## Scenario
You are tasked with testing a registration form that has the following input fields:
- Age: The valid age range is between 18 and 120 (inclusive).
- Email: The email should be in a valid format (e.g., user@domain.com).
- Password: The password should be between 8 and 20 characters (inclusive) and contain at least one uppercase letter, one lowercase letter, and one digit.

## Instructions

### Task 1: Identify Equivalence Classes for Age
1. Identify the valid equivalence classes for the Age field.
2. Identify the invalid equivalence classes for the Age field.
3. Fill in the table below with the identified equivalence classes.

| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|----------------------------|
| Age         |                           |                            |

### Task 2: Identify Equivalence Classes for Email
1. Identify the valid equivalence classes for the Email field.
2. Identify the invalid equivalence classes for the Email field.
3. Fill in the table below with the identified equivalence classes.

| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|----------------------------|
| Email       |                           |                            |

### Task 3: Identify Equivalence Classes for Password
1. Identify the valid equivalence classes for the Password field.
2. Identify the invalid equivalence classes for the Password field.
3. Fill in the table below with the identified equivalence classes.

| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|----------------------------|
| Password    |                           |                            |

### Task 4: Discuss and Share
1. Discuss your findings with your group.
2. Be prepared to share your approach and results with the class.

## Considerations
- Think about the possible valid and invalid values for each input field.
- Consider the boundary values and any specific format requirements.
- Remember that equivalence partitioning helps in reducing the number of test cases while still covering the important scenarios.

<details>
  <summary>Click here to see the answers</summary>

### Task 1: Identify Equivalence Classes for Age
| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|----------------------------|
| Age         | - 18 to 120               | - Below 18<br>- Above 120<br>- Non-numeric |

### Task 2: Identify Equivalence Classes for Email
| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|----------------------------|
| Email       | - Valid email format (e.g., user@domain.com) | - Missing @ symbol<br>- Missing domain<br>- Invalid characters |

### Task 3: Identify Equivalence Classes for Password
| Input Field | Valid Equivalence Classes | Invalid Equivalence Classes |
|-------------|---------------------------|----------------------------|
| Password    | - 8 to 20 characters<br>- Contains at least one uppercase letter, one lowercase letter, and one digit | - Less than 8 characters<br>- More than 20 characters<br>- Missing required character types |

</details>

Remember, practice makes perfect, so don't worry if it takes a bit of time to get the hang of it. With equivalence partitioning in your testing toolbox, you'll be able to design more effective and efficient test cases in no time! 💪

Happy testing! 🎉
