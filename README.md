# Kamisafe Customer Support Assistant
This is a conversational AI powered by Groq. It is designed to provide support to Kamisafe customers, a telecommunication company that deals with the sales of phones and other accessories in a polite and friendly manner. It assists the customers with inquiries, complaints and feedback, relating to Kamisafe products.

## Setup Instructions
To use this project, follow these steps:

1. **Clone the Repository**:
git clone <repository-url>
2. **Navigate to the Project Directory**:
```
cd <project-directory>
```
3. **Set Up a Python Virtual Environment and Activate It**:
```
python -m venv myenv
myenv\Scripts\activate
```
4. **Install the Required Packages**:
```
pip install -r requirements.txt
```
5. **Create a .env in the root directory of your project and add your Groq API key.
```
GROQ_API_KEY=<your-api-key-here>
```

## How to Run the Assistant

1. **Navigate to the project directory in your terminal**:
```
cd [your project directory]
```
2. **Run the main Python script from the terminal or command prompt.**
```
python [customer assistant.py]
```

## Example Usage

**User**: Hi! I am Glory and I want to make inquiries about the available Android phones.
**Assistant**: Hello Glory! Welcome to Kamisafe. Thank you for reaching out. We have a wide range of Android phones available from top brands like Samsung, Google Pixel, Xiaomi, and more. Could you let me know what you're looking for?

## Limitations 
**Inability to handle complex issues**: The assistant currently offers only basic guidance and may need to escalate more complex concerns to human support representatives for proper resolution.

**High Dependency on Keywords**: The assistant relies heavily on predefined keywords to generate appropriate responses. As a result, any deviation in phrasing or vocabulary may lead to misinterpretation or no response at all.


## Future Improvements
**Enhanced Context Handling**: Implementing memory functionality to retain and reference past conversations will improve the assistant’s understanding of ongoing interactions, making it more effective in providing continuous support.

**Expanded Response Range**: Training the model on a wider variety of scenarios and user inputs will enable it to handle a broader spectrum of customer inquiries beyond the current limitations.

**Integration with Human Agents**: Enabling seamless escalation to human support agents for issues beyond the assistant’s capabilities will ensure timely and accurate responses, enhancing the overall customer experience.

## License
This project is licensed under the MIT License.