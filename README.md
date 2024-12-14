# Project: Image Generation using OpenAI API

## Description
This project demonstrates how to use the OpenAI API to generate images based on a provided prompt. The application sends a POST request with the required payload to the API and processes the response to download and save the generated images.

## Tech Stack
- **Python**: For scripting and making API requests.
- **Requests Library**: To handle HTTP requests for communication with the OpenAI API.
- **JSON**: For configuration management and payload handling.

## Getting Started
### Prerequisites
1. **Python Environment**: Ensure Python 3.x is installed on your system.
2. **Dependencies**: Install the `requests` library using the command:
   
   ```
   pip install requests
4. OpenAI API Key: Obtain an API key from the OpenAI platform.
5. Configuration File: Create a config.json file in the project directory with the following structure:# Project: Function Frontend

```
{
    "api_key": "your_openai_api_key",
    "url": "https://api.openai.com/v1/images/generations",
    "filename": "generated_image",
    "headers": {
        "Content-Type": "application/json"
    },
    "payload": {
        "prompt": "An astronaut exploring the surface of a distant planet, with unusual rock formations, a vibrant sunset, and a large, mysterious moon in the sky.",
        "n": 1,
        "size": "1024x1024",
        "response_format": "url",
        "user": "1234"
    }
}

```
## Steps to Run the Project
1. Clone the repository or copy the script gen_img.py and config.json to your project folder.
2. Ensure the config.json file contains valid API credentials and a properly formatted payload.
3. Execute the script:
```
python gen_img.py
```
4. If successful, the script will save the generated images in the current directory.

## Authors

Vanshaj

vanshajsen16@gmail.com
