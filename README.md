# Financial-Risk-Management

# Problem Statement:-
Julie Kavoli, Manager for Project Development at Bluejay Natural Gas, would now like to find the optimal set of project proposals to approve.

The solution should maximize the total NPV from the approved projects. It also must satisfy the constraints imposed by CEO Cordelia Kareeni and the three functional areas:

Capital expenditures over the three years should not exceed $10 billion.

Capital expenditures in any single year should not exceed $4 billion.

At least one project must be approved for each functional area.

# Solution:-
![Image](https://github.com/user-attachments/assets/e9482014-f5ed-4e95-951f-d471e8039df1)
Constraints Considered
Total Capital Budget Constraint:
Total capital expenditures across all three years must not exceed $10 billion.
//
//
Annual Capital Limit Constraint:
Capital expenditures in any individual year must not exceed $4 billion.
Functional Area Representation Constraint:
At least one project must be selected from each of the following functional areas:
Supply
Transportation
Storage
Approach
Using binary decision variables, we represented whether each project should be approved (1) or not (0). The total NPV is then modeled as the sumproduct of the binary decision variables and the respective NPV of each project.
A linear programming (LP) model was created in Excel using the Solver tool, with the objective to:
Maximize total NPV
While satisfying all capital and functional constraints mentioned above
![Image](https://github.com/user-attachments/assets/94a29195-d285-4a22-993c-71e297e89765)
