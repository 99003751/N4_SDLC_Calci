# TEST PLAN:


# Binary Conversion
 | ID | Input | Expected Output | Actual Output | Scenario              |
|----|-------|-----------------|---------------|------------------------|
| B1 |100    |    4,4          |  4,4          |    REQUIRMENT Based    |
| B2 |111    |    7,7          |  7,7          |    Requirment Based    |
| D1 |4      |    100,4        |  100,4        |    Requirment Based    |
| D2 |15     |    1111,F       |  1111,F       |    Scenario Based      |
| D3 |-10    |Invalid Input    |     -         |    Bondary Condition   |
| D4 |2.8    |Invalid Input    |     -         |    Boundary Condition  |
| D5 |-2.8   |Invalid Input    |     -         |    Boundary Condition  |
| D7 |1024   |Error,400        |   400         |    Boundary Condition  |
| B3 |-100   |Invalid Input    |     -         |    Boundary Condition  |
| B3 | A     |Invalid Input    |     -         |    Boundary Condition  |

B - Binary Input, D - Decimal Input
# Trigonometric Conversions

| Test ID 	| input    	| expected output 	| actual output 	| status 	|
|---------	|----------	|-----------------	|---------------	|--------	|
| T1      	| sine 0   	| 0.0             	|               	|        	|
| T2      	| sine 30  	| 0.5             	|               	|        	|
| T3      	| sine 180 	| 0               	|               	|        	|
| T4      	| sine 210 	| -0.5            	|               	|        	|
| T5      	| cos 0    	| 1               	|               	|        	|
| T6      	| cos 180  	| -1              	|               	|        	|
| T7      	| tan 45   	| 1               	|               	|        	|
| T8      	| tan 90   	| 0               	|               	|        	|
| T9      	| sine 48  	| 0.74314483      	|               	|        	|
| T10     	| cos 72   	| 0.30901699      	|               	|        	|


# Dimensions Conversion

| Test ID |   Inputs                    | Expected Output | Actual Output |    Status    |
|---------|-----------------------------|-----------------|---------------|--------------|
| TI 1    | gram to kilogram 1000       | 1               |               |              |
| TI 2    | inch to meter 5             | 0.127           |               |              |
| TI 3    | Fahrenheit to Celsius 97.5  | 36.3888         |               |              |
| TI 4    | kilogram to pounds 20       | 44.0924         |               |              |
| TI 5    | centimeter to foot 32       | 1.0498          |               |              |
| TI 6    | pounds to gram 25           | 11339.8         |               |              |
| TI 7    | meter to kilometer -25      | Invalid         |               |              |
| TI 8    | Celsius to Fahrenheit -25   | -13             |               |              |
| TI 9    | gram to kilogram -5900      | Invalid         |               |              |

# Arithmetic Operations

| Test Id | Input                | Expected Output | Actual Output |   Status   |
|---------|----------------------|-----------------|---------------|------------|
| T1      | Addition 2,3         | 5               |               |            |
| T2      | Subtraction 5,1      | 4               |               |            |
| T3      | Multiplication 2,5   | 10              |               |            |
| T4      | Division 18,6        | 3               |               |            |
| T5      | Addition -2,5        | 3               |               |            |
