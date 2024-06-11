# AI Brand Name Generator

Welcome to the AI Brand Name Generator repository! This innovative project is designed to assist users in generating unique and creative brand names tailored to their industry and specific keywords using advanced LSTM (Long Short-Term Memory) deep learning models. Our goal is to provide a comprehensive branding solution that simplifies the creative process for individuals and businesses alike.

## Features

- **Brand Name Generation**: Input your industry and keyword to receive relevant and innovative brand name suggestions.
- **Color Palettes**: Receive curated color palette recommendations suited to your industry, ensuring a cohesive visual identity.
- **Font Recommendations**: Get font suggestions that enhance the aesthetic and readability of your brand's materials.
- **Logo Preferences and Generation**: Specify your logo style preferences and generate logos using the DALL-E 3 API, offering quick and personalized logo solutions.

## Technology Stack

- **Backend**: Built with Flask, using SQLite for the database.
- **Frontend**: Developed with Vite and React for a dynamic and responsive user experience.
- **Model**: LSTM(Long Short Term Memory) Model for name generation based on industry and keywords
- **Logo Generation**: Integrated Dall-E-3 API Key for logo generation

## Getting Started

To get started with the AI Brand Name Generator, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/ai-brand-name-generator.git
    cd ai-brand-name-generator
    ```

2. **Backend Setup**:
    - Create a virtual environment:
        ```sh
        python3 -m venv venv
        source venv/bin/activate
        ```
    - Install dependencies (including TensorFlow version 2.15.0):
        ```sh
        pip install -r requirements.txt
        pip install tensorflow==2.15.0
        ```
    - Run the Flask server:
        ```sh
        flask run
        ```

3. **Frontend Setup**:
    - Navigate to the frontend directory:
        ```sh
        cd frontend
        ```
    - Install dependencies:
        ```sh
        npm install
        ```
    - Run the development server:
        ```sh
        npm run dev
        ```

4. **API Keys**:
    - Configure the necessary API keys for the DALL-E 3 integration by adding them to your environment variables or a configuration file as specified in the project documentation.

## Loading the Model and Adding Dataset

1. **Prepare the Dataset**:
    - Ensure your dataset is in the correct format (e.g., CSV) and contains the necessary data (industry, keywords, etc.).
    - Place the dataset file in the `backend/data` directory.

2. **Load the Model**:
    - Ensure your pre-trained LSTM model file is in the `backend/models` directory.
    - Modify the `load_model.py` script to load your specific model:
        ```python
        from keras.models import load_model

        model = load_model('models/your_model.h5')
        ```

3. **Update the Backend to Use the Dataset**:
    - Modify the `app.py` script to load and use the dataset for generating brand names:
        ```python
        import pandas as pd

        # Load the dataset
        dataset = pd.read_csv('data/your_dataset.csv')


## Contributions

We welcome contributions to this project. If you have ideas for new features, improvements, or bug fixes, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

Please review our contribution guidelines before getting started.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
