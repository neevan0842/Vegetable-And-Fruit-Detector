# Vegetable And Fruit Detector

#### Video Demo: https://youtu.be/BYfmAKx_Pm0

## Description

This is a Flask web application that allows users to upload images, which are then processed to predict the content of the image. The application specifically predicts the type of vegetable depicted in the uploaded image.

## Project Files

- **app.py**: The main Python script containing the Flask application. It defines routes, views.

- **helper.py**: Code related to the machine learning model used for image prediction. It loads the model and preprocesses images for prediction.

- **templates**: HTML templates used for rendering web pages, including the home page.

- **static**: Contains static assets such as CSS stylesheets and uploaded images

- **Sample Image**: Contain a few image for testing.

### Recognizable Fruits and Vegetables

- Apple
- Banana
- Beetroot
- Bell Pepper
- Cabbage
- Capsicum
- Carrot
- Cauliflower
- Chilli Pepper
- Corn
- Cucumber
- Eggplant
- Garlic
- Ginger
- Grapes
- Jalepeno
- Kiwi
- Lemon
- Lettuce
- Mango
- Onion
- Orange
- Paprika
- Pear
- Peas
- Pineapple
- Pomegranate
- Potato
- Radish
- Soy Beans
- Spinach
- Sweetcorn
- Sweet Potato
- Tomato
- Turnip
- Watermelon

### Features

- Users can upload images.
- The uploaded images are resized for processing.
- A machine learning model predicts the type of vegetable/fruit in the image.
- The predicted vegetable name is displayed to the user .


## Requirements

Before you begin, ensure you have met the following requirements:

- **Python**: Your system should have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

### Python Packages

Install the required Python packages using `pip`:

```bash
pip install -r requirements.txt
```

## Installation

Follow these steps to set up your Flask application:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/neevan0842/Vegetable-And-Fruit-Detector.git
    ```

2. **Change Directory**:

    ```bash
    cd your-flask-app
    ```

3. **Create a Virtual Environment (Recommended)**:

    ```bash
    python -m venv venv
    ```

4. **Activate the Virtual Environment**:

    On Windows:
    ```bash
    venv\Scripts\activate
    ```

    On macOS and Linux:
    ```bash
    source venv/bin/activate
    ```

5. **Run the Application**:

    ```bash
    flask run
    ```

Your Flask application should now be set up with the necessary dependencies.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code for personal and commercial purposes. Refer to the [LICENSE](LICENSE.txt) file for more details.

---
