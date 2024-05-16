## AI-Powered Recipe Generation  

This Streamlit web app leverages Google's GenerativeAI service (Gemini-Pro) to create recipes based on uploaded food images.


![Cookies](food_images/cookies.jpg)

## Run on Streamlit  
You can try this app on Streamlit:  
[Recipe cretor](https://nutrients-tracker.streamlit.app)


## 1. Features:

- **Image Upload:** Upload an image of a dish.
- **AI-powered Image Analysis:** Gemini-Pro analyzes the image to identify the ingredients in the dish.
- **Recipe Generation:** Based on the identified ingredients, Gemini-Pro generates a recipe with a list of ingredients and instructions.

## 2. Requirements:

- Python 3.x
- Streamlit (`pip install streamlit`)
- `dotenv` library (`pip install python-dotenv`)
- Pillow library (`pip install Pillow`)
- Google Cloud Project with GenerativeAI API enabled ([Google Cloud Generative AI](https://cloud.google.com/ai/generative-ai))

## 3. Setup:

1. Create a virtual environment (recommended): `python -m venv venv`
2. Activate the environment: `source venv/bin/activate` (Windows: `venv\Scripts\activate`)
3. Install dependencies: Refer to the requirements section and install the necessary libraries.
4. Create a `.env` file in the project directory:
   - Add `GOOGLE_API_KEY=<YOUR_API_KEY>` (replace with your GenerativeAI API key)

## 4. Running the App:

1. Open a terminal in the project directory.
2. Run the app: `streamlit run app.py`
3. Access the app in your web browser at http://localhost:8501.

## 5. Usage:

1. Click "Choose an image..." and upload a picture of a dish.
2. Click the "Tell me the recipe" button.
3. The app will analyze the image, generate a recipe based on the identified ingredients, and display it in the "The Recipe is" section.

## 6. Disclaimer:

- This is a basic example using a free-tier API. The accuracy and detail of recipes may vary.
- Consider the limitations of image analysis and the quality of uploaded images for best results.

## 7. Note

- This README assumes you have completed initial setup and configured your Google Cloud Project with the GenerativeAI API.