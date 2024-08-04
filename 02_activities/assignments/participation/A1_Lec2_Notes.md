Lec 2
--Case Study
We cannot trust the result if image/data manipulation
Dr.Elisabeth work for image manipulation
We cannot trust data visualization if data manipulation

Reproducibity
-repeatable
-high requirement for publication
-ethical: accountable for decisions
-practical: easier to change
=> It does not mean Correction

How make Reproducibity
-Work programmatically
-Work in plain text
-Comment your code: what are you doing/what the code use for

Activity
# Set the seed for reproducibility of random numbers
 np.random.seed(613)
# Create an array of 50 values from 0 to 49
x = np.arange(50) 
# Generate 50 random integers between 0 and 100
 y = np.random.randint(0, 100,50)
#  Create a figure and an axis with a specified figure size
fig, ax = plt.subplots(figsize=(5, 3))
## Create a scatter plot of x vs y
ax.scatter(x,y)

=> When commenting your code, it's helpful to include:
Purpose of the Code: Explain what the code is supposed to accomplish.
Key Steps: Highlight and describe the main steps or sections of the code.
Non-Obvious Logic: Clarify any complex or non-intuitive parts of the code.
Inputs and Outputs: Describe the expected inputs and outputs, especially for functions and scripts.
Parameters and Arguments: Explain the role of important parameters and arguments.
Dependencies: Note any important dependencies or required libraries.
=> How do you write a 'good' comment?
A good comment should be:
Clear and Concise: Use simple and straightforward language.
Relevant: Focus on explaining why the code does something, rather than what the code does (which should be clear from the code itself).
Up-to-Date: Ensure comments are accurate and reflect the current state of the code.
Consistent: Follow a consistent style and format for commenting throughout the codebase.


Visualization- US Gun
What information we can get: The killed people by gun in US in 2018- age, gender
Mutual colour cannot clear figure out by the graph // related data

Three important qualities of data visualization:
Is the visualization pleasing to look at? → Aesthetic
Does the visualization accurately and honestly present data? → Substantive
Can we understand what message the maker of the visualization is attempting to
convey? → Perceptual

What purpose for using data:
Persuading
Comparison
Evaluating
Exploring

What level of audience:
Age
Education
Experience
Accessibility

What medium
Print
Web
Poster
Presentation

Cognitive psychology: UX design

Principles
-Proximity: close to
-Similarity: similar objects are grounded
-Continuity
-Closure

-We cannot control Intrinsic/ Germance, but we always can control Extraneous

=> Accurate vs.Approximate interpretation → relational values or areas
(approximate) increase cognitive load compared to absolute values or position
(accurate)
Concise vs.
=> Explanatory vs. Exploratory composition → a chart that the audience navigates
alone increases cognitive load compared to a chart that they are guided through
step-by-step

Resources: Online

