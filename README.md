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
    - Install dependencies:
        ```sh
        pip install -r requirements.txt
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
