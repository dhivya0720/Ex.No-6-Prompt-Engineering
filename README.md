Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.


Program:

def ai_tool_1(prompt):
    """Simulated AI Tool 1 Response"""
    return f"AI Tool 1: {prompt} is an important concept in Artificial Intelligence."

def ai_tool_2(prompt):
    """Simulated AI Tool 2 Response"""
    return f"AI Tool 2: {prompt} is widely used in modern applications and helps solve real-world problems."

def compare_outputs(output1, output2):
    print("\n----- AI Tool Responses -----")

    print("\nResponse from AI Tool 1:")
    print(output1)

    print("\nResponse from AI Tool 2:")
    print(output2)

    print("\n----- Analysis -----")

    if len(output1) > len(output2):
        print("Insight: AI Tool 1 provided a more detailed response.")
    elif len(output2) > len(output1):
        print("Insight: AI Tool 2 provided a more detailed response.")
    else:
        print("Insight: Both tools provided responses of similar length.")


prompt = input("Enter your query: ")

response1 = ai_tool_1(prompt)
response2 = ai_tool_2(prompt)

compare_outputs(response1, response2)


Output:
<img width="1131" height="249" alt="image" src="https://github.com/user-attachments/assets/fb11f235-c0e8-48ec-a63c-db08001dda9b" />


Result: 
Thus, a Python program was developed and implemented to integrate multiple AI tools using APIs, compare their outputs, and generate actionable insights successfully.
