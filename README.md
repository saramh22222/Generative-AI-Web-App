# Generative AI Web App

This web application utilizes Generative AI to train and generate responses based on user input. The app is built using Flask, a micro web framework for Python.

## Getting Started

To run the web application, follow these steps:

1. Install the required Python packages:
   ```bash
   pip install Flask google-generativeai
   ```

2. Run the Flask application:
   ```bash
   python your_app_name.py
   ```
   Replace `your_app_name.py` with the name of the Python script containing your application.

3. Open your web browser and navigate to [http://localhost:5000/](http://localhost:5000/) to access the Generative AI Web App.

## Features

### Training the Model

1. Enter the number of training examples in the provided input field.
2. Click the "Create Training Examples" button to dynamically generate input and output fields for training.
3. Enter the training data in the generated input fields.
4. Click the "Train Model" button to train the model with the provided examples.

### Generating Responses

1. Enter a testing input in the designated input field.
2. Click the "Generate Response" button to generate a response based on the trained model.
3. View the testing input and the generated response displayed on the web page.

## Web App Structure

The web app is structured as follows:

- `index.html`: The HTML template containing the structure and styling of the web page.
- `your_app_name.py`: The main Python script implementing the Flask web application.
  
The web page includes sections for training the model and generating responses. The UI is designed to be user-friendly, allowing for an interactive experience.

## Dependencies

- Flask: Micro web framework for Python.
- google-generativeai: Library for accessing Generative AI models.

## Configuration

Ensure that you have the necessary API key for the Generative AI model. You can configure it in the Python script:

```python
import google.generativeai as palm
palm.configure(api_key="YOUR_API_KEY")
```

Replace `YOUR_API_KEY` with the actual API key obtained for accessing the Generative AI model.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

- The web application uses Generative AI provided by Google's GenerativeAI API.

Feel free to customize and extend the application based on your requirements. If you encounter any issues or have suggestions for improvements, please contribute to the project.
