# disco-project-Hello , and welcome to this project where we’ll be diving into a Python script designed to solve an optimization problem related to course assignments for professors.
We express our sincere gratitude to Mr. Snehaanshu Sir for providing us with the invaluable opportunity to engage in this assignment. While we may not have achieved success in all test cases, the learning experience has been tremendously enriching.
Our journey commenced with a thorough review of research papers online, including articles published by esteemed researchers like Nancy Maribel Arratia Martinez. This initial exploration aimed to discern the potential applications of bipartite graphs and how they could be leveraged to reach a viable algorithmic solution.
Although our initial path led us to the Hungarian Algorithm, the complexity of the task required further insights. Over the past month, we actively sought knowledge from students enrolled in optimization courses, engaging in insightful conversations to deepen our understanding of the algorithm's nuances.
Despite our efforts to connect with Professor Mayank Goel, his busy semester schedule posed challenges. Nevertheless, armed with the foundational knowledge acquired, we delved into the application of the Hungarian Algorithm.
In the upcoming discussion, we will elucidate our progression in navigating through this algorithm. This journey, albeit challenging, has been a profound learning experience, underscoring the importance of persistence and collaborative learning in the realm of optimization algorithms."
Let’s explore the functionalities and the underlying Hungarian Algorithm employed in this code.”

[Libraries and Functions]

“Firstly, we import necessary libraries such as NumPy for numerical operations and the deepcopy function for creating deep copies of objects. The script comprises several key functions, each serving a specific purpose. Let’s briefly go over these functions.”

[Hungarian Algorithm Overview]

“Before delving into the code, let’s understand the Hungarian Algorithm. This algorithm is used for solving assignment problems, where the goal is to find the optimal assignment of tasks to resources, minimizing the overall cost. In this case, tasks represent courses, and resources are professors.”

[Input Reading]

“The script begins by reading input from an external file. The file structure includes a list of courses and information about professors, their types, and the courses they can teach. Let’s see how the code processes this input to set up the problem.”

[Matrix Initialization]

“The Hungarian matrix is crucial to this algorithm. It’s initialized with values representing the cost of assigning a professor to a course. Infinity is used to signify unavailability. Let’s take a closer look at how this matrix is constructed.”

[Professor Information Processing]

“As the script progresses, it processes information about professors and their course assignments. The Hungarian matrix is updated accordingly, reflecting the costs associated with each assignment. We’ll see how professors are categorized and their preferences considered.”

[Optimization and Solution]

“Now comes the heart of the script—the optimization phase using the Hungarian Algorithm. The code minimizes costs by iteratively adjusting the matrix. We’ll explore how this process unfolds, leading to an optimal assignment of professors to courses.”

[Error Handling]

“To ensure constraints are met, the script incorporates error handling. If constraints aren’t satisfied, the script provides a clear error message. Understanding how the code handles these situations is crucial for its robustness.”

[Results and Output]

“As the optimization concludes, the script outputs the minimum cost and the optimal assignments. It’s noteworthy that there might be multiple optimal solutions. We’ll explore how the script deals with this and presents the results.”

[Conclusion]

“To wrap up, we’ve covered the essentials of this Python script designed for course assignment optimization. I encourage you to explore the code further, experiment with different inputs, and gain a deeper understanding of how the Hungarian Algorithm can be applied to real-world problems


MADE BY
MAHATVA GARG (2021B1A72408G)
MIHIKA SINGHAL(2022A7PS0345G)
PRISHA GUPTA(2022A7PS0164G)
