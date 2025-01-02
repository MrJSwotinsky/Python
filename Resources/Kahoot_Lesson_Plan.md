# Python
Tuesday, December 17th 2024

### Kahoot Review for Unit 3 Exam (Data Collections)

**AIM:** What key understandings, knowledge, skills, and practices do we need to master to show what we know about lists, tuples, and dictionaries on tomorrow's unit exam?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS61XT.3</ins>: Write and analyze programs and code segments in relation to control flow.
<br><ins>IEC.TYS61XT.4</ins>: Write and analyze programs and code segments in relation to data collections.

**SUCCESS CRITERIA:**
- [ ] I am able to describe characteristics of lists, tuples, and dictionaries.
- [ ] I am able to accurately analyze code segments that involve lists, tuples, and dictionaries.

<table>
  <tr>
    <td><b>DO NOW:</b><br>Connect to today's Kahoot.
  </tr>
</table>

**AGENDA:**

1. Join Kahoot!
2. Show what you know!
    *  Be prepared to justify your reasoning.
    *  Be prepared to engage in small group discussions.
    *  Key Concepts:
        * Lists:
            * Syntax
            * Referencing Elements 
            * Slices
            * Negative indices
            * Out of range exceptions
            * Copies vs. Pointers
            * `.append()`, `.remove()`, `.insert()`, and `del`
        * Tuples:
            * Syntax
            * Characteristics (e.g. tuples are immutable)
            * Iteration with tuples
        * Dictionaries:
            * Syntax
            * Key-value pairs
            * Iteration with dictionaries
      * Key Strategies:
          * Code tracing
          * Process of elimination 
3. Summary / Close:
    * Final Questions / Comments
    * Final Reflection Questions (based on live data)
   
**HOMEWORK:** <br>
Leverage your resources (OpenEDG, Code Analysis Practice Sets, Notes, **a study group session with your debugging buddies**, etc.) to prepare for tomorrow's Unit Exam.  

**DIFFERENTIATION STRATEGIES:** <br>
1.  Provide multiple entry paths by providing students with optional access to resources during Kahoot! (Students may use edube.org, code analysis practice sets, and notes).  Students who need more support may leverage resources to support them in analyzing code to determine correct responses.  Students who need less support may opt to challenge themselves by attempting to analyze code without referring to resources.
2.  Provide tiered questions allowing students to engage at varying levels of difficulty.

**Sample Mild Question/**

> Which of the following will be displayed as a result of the code segment below?
> ```python
> powers = [1, 2, 4, 8, 16]
> print(powers[2:4])
> ```

**Sample Medium Question/**

> Write a line of code to add 95 gloves to `inv`.

**Sample Spicy Question/**

> What is the expected output of the following code?
> ```python
> bools = (False, True, False)
> inner = bools[:1]
> count = 0
> for entry in inner[-1:]:
>   if entry:
>     count += 1
> print(count)
> ```

**ASSESSMENT STRATEGIES:** <br>
1.  Leverage immediate feedback from Kahoot! to pivot as needed during game.
2.  Utilize call and response questions to check for understanding and pivot as needed during game.

**Example 1/**
> What will happen if we try to reference a single index in a list that is out of range?<br>
> What will happen if we try to reference an index that is out of range in a slice?

**Example 2/**
> Why **can't** .append() be used to add an element to a tuple?<br>
> Why **can** we concatenate tuples?

**Example 3/**
> Explain the key difference between the following two code segments:
> ```python
> inventory = {'hats':100, 'gloves':95, 'scarves':220}
>
> for product in inventory.keys():
>   print(product[1], end = '')
> ```
>
>  ```python
> inventory = {'hats':100, 'gloves':95, 'scarves':220}
>
> for product in inventory.items():
>   print(product[1], end = '')
> ```

3.  Utilize summary data from Kahoot! as formative assessment to desigin instruction for PCEP exam review in January.

**QUESTIONING AND DISCUSSION STRATEGIES:** <br>
1.  Engage students in accountable talk by challenging them to justify their own and their peer's responses during game.
2.  Engage students in small group discussion periodically throughout game using turn and talk.
