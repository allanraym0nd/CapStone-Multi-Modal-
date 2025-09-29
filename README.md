**Groq Multimodal Agent: Image and Text Analysis**

This project uses Python in a Colab environment to perform multimodal analysis by combining a user-uploaded image with a custom text prompt, powered by Groq's super-fast Llama 4 Scout model.

**Key Features**

Speed: Leverages the Groq LPU for high-speed analysis.

Multimodal: Analyzes both an image and a user's specific question or instruction (text prompt).

Secure Setup: Reads the GROQ_API_KEY securely from Google Colab Secrets.

Dynamic Input: The user provides the text prompt at runtime (not hardcoded).

**Quick Start Guide**

1. Set up your API Key
   
Open the Secrets tab in Google Colab.

Add a new secret named: GROQ_API_KEY.

Set its value to your key obtained from the Groq Console.

2. Run the Code
   
Paste and run the provided Python code in a Colab cell.

**3. Usage**

When prompted, enter your custom question.

Click "Choose Files" and upload an image (JPG or PNG).

The agent will process both inputs and return a detailed response.

**Model and Dependency**

Model: meta-llama/llama-4-scout-17b-16e-instruct

Dependencies: groq, pillow (PIL)
