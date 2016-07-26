The in-person interview
=======================

Three themes should be running constantly throughout the entire interview:

1. Treat the candidate as a rockstar.
2. Present your workplace and the position in the best possible light.
3. Is the candidate smart and gets things done?

Preparation
-----------

Schedule the interview in a nice room, for example:

- A room with a view
- A room near the coolest teams
- A room near attractive facilities, for example the free coffee machines

Reception
---------

Receive the person with a relaxed, casual attitude, and offer a drink.
If you have free coffee, this is a good opportunity to show that off.

The interview
-------------

Before you can start asking the questions that you really want to ask,
you need to first get the candidate to relax.
It's almost impossible to see the true abilities of a stressed out and nervous candidate,
and that's not good for anyone.

Start by asking about recent experience.
Try to find something the candidate is passionate about.
What was interesting?
What was difficult?
This is not a test.
Show real interest and curiosity in the candidate's recent work.

Once the candidate is relaxed enough,
proceed with an easy coding question.
Consider this example for a junior position:
write a function to calculate the sum of a list of integers.
For example, if the list contains the integers 1, 7, 3,
the function should return 11.

Ask the candidate to first explain the algorithm before writing anything.
Make sure you both agree on what is the task.
It's a good sign if the candidate asks clarifying questions.
If the algorithm sounds like it might work,
let the candidate start coding.
Encourage the candidate to think out loud the implementation steps while writing.

The candidate may write something like this:

    int test(List nums) {
        int sum = 0;
        for (int num : nums) {
            sum += num;
        }
        return sum;
    }

It may be tempting to ask "why did you name the function 'test'",
or "why didn't you specify the type of the list",
but there won't be good answer to these questions,
and the candidate may feel humiliated for such silly mistakes.

Propose this alternative writing style of the loop for the sake of a conversation:

        for (int i = 0; i < nums.length; i++) {
            sum += nums[i];
        }

And chat about these topics:

- Is this the same?
- Is there a practical difference?
- What is the time complexity of the each variant?
- What if `nums` is a linked list?

As a follow-up task,
ask the candidate to reimplement the same function using recursion.
Let the candidate adjust the method signature or introduce a helper function.
Recursion is a great topic,
because it requires a real programmer's mind to get it,
so any struggle here should be a warning sign.

These questions can be answered well using good working knowledge of programming fundamentals, and can reveal smartness.

TODO

The closing
-----------

TODO
