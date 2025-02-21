# Create-loops

<h1>Activity: Create loops</h1>

<h1>Introduction</h1>
As a security analyst, some of the measures you take to protect a system will involve repetition. As an example, you might need to investigate multiple IP addresses that have attempted to connect to the network. In Python, iterative statements can help automate repetitive processes like these to make them more efficient.

In this lab, you will practice writing iterative statements in Python.

<h1>Scenario</h1>
You're working as a security analyst, and you're writing programs in Python to automate displaying messages regarding network connection attempts, detecting IP addresses that are attempting to access restricted data, and generating employee ID numbers for a Sales department.

<h1>Task 1</h1>
In this task, you'll create a loop related to connecting to a network.

Write an iterative statement that displays Connection could not be established three times. Use the for keyword, the range() function, and a loop variable of i. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/1aa26989-e6c3-461c-b571-9c3a494271ae)

<h1>Task 2</h1>
The range() function can also take in a variable. To repeat a specified action a certain number of times, you can first assign an integer value to a variable. Then, you can pass that variable into the range() function within a for loop.

In your code that displays a network message connection, incorporate a variable called connection_attempts. Assign the positive integer of your choice as the value of that variable and fill in the missing variable in the iterative statement. Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell. Test out the code with different values for connection_attempts and observe what happens.

![image](https://github.com/user-attachments/assets/50524179-01c3-46f5-8a04-db3b33312ead)

<h1>Task 3</h1>
This task can also be achieved with a while loop. Complete the while loop with the correct code to instruct it to display "Connection could not be established." three times.

In this task, a for loop and a while loop will produce similar results, but each is based on a different approach. (In other words, the underlying logic is different in each.) A for loop terminates after a certain number of iterations have completed, whereas a while loop terminates once it reaches a certain condition. In situations where you do not know how many times the specified action should be repeated, while loops are most appropriate.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/e26c664d-7ec9-4ed5-ac40-e4003bd0d45a)

<h1>Question 1</h1>
What do you observe about the differences between the for loop and the while loop that you wrote?

The messages outputted from both loops were identical. The logic is what differed between the two loops. In the for loop, the loop variable i was automatically defined in the loop header, and it was updated automatically in each iteration. In the while loop, the loop variable connection_attempts had to be defined before the loop header, and it had to be explicitly updated inside the loop body.

<h1>Task 4</h1>
Now, you'll move onto your next task. You'll automate checking whether IP addresses are part of an allow list. You will start with a list of IP addresses from which users have tried to log in, stored in a variable called ip_addresses. Write a for loop that displays the elements of this list one at a time. Use i as the loop variable in the for loop.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/59f6aadd-d711-4399-8bbf-91baf85c3031)


<h1>Task 5</h1>
You are now given a list of IP addresses that are allowed to log in, stored in a variable called allow_list. Write an if statement inside of the for loop. For each IP address in the list of IP addresses from which users have tried to log in, display "IP address is allowed" if it is among the allowed addresses and display "IP address is not allowed" otherwise.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/7c3dc87f-9073-4f)

<h1>Task 6</h1>
Imagine now that the information the users are trying to access is restricted, and if an IP address outside the list of allowed IP addresses attempts access, the loop should terminate because further investigation would be needed to assess whether this activity poses a threat. To achieve this, use the break keyword and expand the message that is displayed to the user when their IP address is not in allow_list to provide more specifics. Instead of "IP address is not allowed", display "IP address is not allowed. Further investigation of login activity required".

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.78-97d3-a68500692d82)

![image](https://github.com/user-attachments/assets/14fd914d-6adf-4188-a9ba-177382e132f0)

<h1>Task 7</h1>
You'll now complete another task. This involves automating the creation of new employee IDs.

You have been asked to create employee IDs for a Sales department, with the criteria that the employee IDs should all be numbers that are unique, divisble by 5, and falling between 5000 and 5150. The employee IDs can include both 5000 and 5150.

Write a while loop that generates unique employee IDs for the Sales department by iterating through numbers and displays each ID created.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/ccafabca-c807-46bd-9409-3bd4c9b79a17)

![image](https://github.com/user-attachments/assets/874eea44-a50d-4f40-b408-1fe452df4c38)

<h1>Task 8</h1>
You would like to incorporate a message that displays Only 10 valid employee ids remaining as a helpful alert once the loop variable reaches 5100.

To do so, include an if statement in your code.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

![image](https://github.com/user-attachments/assets/4696b0c2-0dc5-40cb-91da-7994bc5c989e)

![image](https://github.com/user-attachments/assets/2e82adec-3806-435d-a842-8354d930eb79)

<h1>Question 2</h1>
Why do you think the statement print(i) is written before the conditional rather than inside the conditional?

The goal is to display every employee ID number that's created, and the loop variable i represents the ID number created in each iteration of the loop. The statement print(i) is written before the conditional, so that the loop is displayed in every iteration. Otherwise, if print(i) was written inside the conditional, the loop variable would only be printed out when it's equal to 5100. (Since the condition in the if statement is i == 5100.)

<h1>Conclusion</h1>
What are your key takeaways from this lab?

- Iterative statements play a major role in automating security-related processes that need to be repeated.
- You can for loops allow you to repeat a process a specified number of times.
- You can use while loops allow you to repeat a process until a specified condition has been met. Comparison operators are often used in these conditions.
- The < comparison operator allows you to check whether one value is less than another.
- The <= comparison operator allows you to check whether one value is less than or equal to another.
- The == comparison operator allows you to check whether one value is equal to another.
  
