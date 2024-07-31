
# Email Classifier

This project is a web application for detecting spam emails using machine learning. The application is built with Streamlit and uses a pre-trained model to classify emails as spam or not spam.

## Features

- **Spam Detection**: Classifies emails as spam or not spam based on the content.
- **User-Friendly Interface**: Simple and intuitive design with a responsive UI.
- **Custom Styling**: Enhanced visuals with custom CSS for buttons and background.

## Demo

Check out the live demo: [Email Classifier](https://github.com/tbhhero/Email_Classifier)

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/tbhhero/Email_Classifier.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Email_Classifier
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

5. Open your browser and go to `http://localhost:8501` to view the app.

## Project Structure

- `app.py`: Main file for the Streamlit app.
- `transform_text.py`: Script for text preprocessing.
- `model.pkl`: Trained machine learning model.
- `vectorizer.pkl`: TF-IDF vectorizer used for transforming text.
- `design.css`: Custom CSS for styling the app.

## Text Preprocessing

The `transform_text` function performs the following steps:

1. **Lowercasing**: Converts all characters in the text to lowercase.
2. **Tokenization**: Splits the text into individual words.
3. **Removing Non-Alphanumeric Characters**: Filters out non-alphanumeric characters.
4. **Removing Stopwords**: Removes common English stopwords.
5. **Stemming**: Reduces words to their root form using the PorterStemmer.

## Usage

1. Enter the email content in the text area.
2. Click on the "Classify" button to determine if the email is spam or not.
3. The result will be displayed at the top of the page.

## Custom CSS

The `design.css` file contains custom styles for buttons and text. The button style uses a gradient background with a smooth transition effect.

## Acknowledgments

- [Streamlit](https://streamlit.io/)
- [nltk](https://www.nltk.org/)
- [Scikit-learn](https://scikit-learn.org/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
