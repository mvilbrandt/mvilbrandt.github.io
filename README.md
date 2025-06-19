# I'm Mason, Welcome to My Website!
<img src = "https://github.com/user-attachments/assets/3b5af849-4cf1-4207-b026-9cf3f946a741" width = "150" height = "225" />

## A Little About Myself
My name is Mason Vilbrandt, and I am a recent graduate of the University of Wisconsin–Madison, where I earned a Bachelor of Science in Data Science and a certificate in Digital Media Analytics. Currently based in Milton, Wisconsin, I am actively pursuing opportunities to apply my analytical skills and data-driven mindset in a professional environment.

I am detail-oriented, passionate about turning data into actionable insights, and eager to contribute to a company that values innovation, precision, and curiosity. Below, you’ll find links to my résumé, project portfolio, and other credentials that highlight my experience and capabilities.

Thank you for taking the time to learn more about me—I look forward to connecting.

## Socials
<img src = "https://github.com/user-attachments/assets/13ba5ca7-d8f8-4862-91b6-7d0085fcd0bf" width = "30" height = "30" /> [LinkedIn](https://www.linkedin.com/in/mason-vilbrandt-2a65ba32b/)

<img src = "https://github.com/user-attachments/assets/df45e54a-48b5-444e-b4db-2fc026c508d8" width = "30" height = "30" /> [Handshake](https://wisc.joinhandshake.com/profiles/z3hse6)

<img src = "https://github.com/user-attachments/assets/111ab23e-e126-4a48-b5ce-36a7fe33c3b0" width = "30" height = "30" /> [Indeed](https://profile.indeed.com/)

<img src = "https://github.com/user-attachments/assets/cc3369cf-fcff-4d07-8228-2c78122922a3" width = "30" height = "30" /> [Instagram](https://www.instagram.com/masonvilbrandt/?next=%2F)

<img src = "https://github.com/user-attachments/assets/da86ed68-8381-435e-8474-d8dbcdee5044" width = "30" height = "30" /> [Facebook](https://www.facebook.com/mason.vilbrandt/)

<img src = "https://github.com/user-attachments/assets/240777fe-4532-4156-bb83-70bed1a0b9a9" width = "30" height = "30" /> [X](https://x.com/MVilbrandt)






## Résumé
<img src = "https://github.com/user-attachments/assets/a33a2b80-78e1-4ca2-8684-6addd1dd6b5d" width = "400" height = "600" />

[download](https://github.com/user-attachments/files/20714970/Mason.Vilbrandt.Resume.pdf)

## Machine Learning Projects

During my final semesters at the University of Wisconsin–Madison, I had the opportunity to work on several collaborative and individual projects that highlight my skills in data analysis, machine learning, and data visualization. Below are links to select projects, including machine learning models and a data visualization project that showcase both my technical abilities and my commitment to clear, impactful storytelling through data.

### ML Project 1: SailCo

This model solves SailCo’s quarterly sailboat production planning problem using two approaches—both framed as minimum-cost network flow (MCNF) models in GAMSPy:

#### Goal
Minimize total costs of:

Regular labor production (400 USD/boat, max 40/quarter)

Overtime labor production (450 USD/boat, unlimited)

Inventory holding (20 USD/boat/month)

while meeting the demand for sailboats over 4 quarters:

Q1: 40

Q2: 60

Q3: 75

Q4: 25
With initial stock of 10 boats.

#### What the Model Does
1. Formulation as an LP (inventory flow model)
Defines decision variables:
Regular, Overtime, and Inventory for each month

Enforces balance constraints to ensure demand is met using:

Inventory carried over

Production via regular/overtime labor

Initial stock

Minimizes total cost using constraints and parameters.

2. Formulation as a MCNF model
Models each quarter and production type as nodes

Defines arcs:

From a master supply node to Regular and Overtime

From Regular/Overtime to monthly nodes (m1, m2, etc.)

From month to month to model inventory transitions

Flow balance equations guarantee the correct number of boats produced, used, and stored

Solves using x[i,j] as the flow variable on each arc.

3. Sensitivity Analysis
Varies initial stock (normally distributed samples)

Re-solves the MCNF model for each scenario

Plots how starting inventory affects total cost

#### Outputs
Optimal cost

Boat production and inventory plan for each month

Visualization of cost vs. initial inventory

#### Summary
This model is a cost-optimized production and inventory planner for SailCo. It decides how many boats to build (regular vs overtime) and how much inventory to carry each quarter to meet demand at minimum cost, while exploring how changes in initial stock affect outcomes. Below is the link to the html file for the model.

[Sailco](https://mvilbrandt.github.io/Sailco.html)

### ML Project 2: Widgets

This optimization model is a Critical Path Method (CPM) model implemented in GAMS using GAMSPy. It is used to determine the minimum project completion time for producing a new product at Widgetco.

#### Key features:
Activities: There are 6 project activities (e.g., training workers, purchasing raw materials, making subassemblies).

Precedence constraints: Some activities must be completed before others can begin (e.g., subassemblies can't be made before training and purchasing materials).

Durations: Each activity has a fixed time duration.

Decision variables: The model finds the optimal start time for each activity (t) and the total project duration (projDur).

#### Objective:
Minimize projDur, the total time to complete all activities, while respecting precedence constraints and activity durations.

#### Summary:
This model schedules project tasks to minimize completion time, identifying the critical path — the longest sequence of dependent tasks that determines the project's minimum duration. Below is the html link to the model.

[Widgets](https://mvilbrandt.github.io/Widgets.html)

## Data Visualization Projects

I have developed a wide range of data visualizations using SQL and RStudio, showcasing my ability to extract, analyze, and present complex datasets in a clear and impactful manner. Below are a few selected examples from a final project in my capstone class for my Digital Media Analytics Certificate.

<img src = "https://github.com/user-attachments/assets/e372f877-c713-4071-9350-8e576cd8200e" width = "500" height = "400" /> <img src = "https://github.com/user-attachments/assets/5a900be2-b5b4-4878-88cd-d5c95fd710d4" width = "500" height = "400" />

<img src = "https://github.com/user-attachments/assets/0fcca4db-e415-4c00-ac85-b7ddff5bd712" width = "1300" height = "650" />




