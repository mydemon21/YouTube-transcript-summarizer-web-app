# YouTube-transcript-summarizer-web-app
Convert YouTube video transcripts into detailed summaries. Input a video URL, and get a summarized text using Google Gemini. Includes a sleek, thumbnail, and interactive features. Built with Python and Streamlit.

## **Features**

- **YouTube Video Transcript Extraction**: Extracts transcripts from YouTube videos using the YouTube Transcript API.
- **Summary Generation**: Creates a summary of the video transcript using Google Gemini Pro.
- **Attractive UI**: Provides a visually appealing and user-friendly interface with a light pastel gradient background and modern design elements.
- **Thumbnail Display**: Shows the video thumbnail for user reference.

## **Prerequisites**

- **Python 3.x**
- **Google Generative AI API Key**: Required for generating summaries.
- **YouTube Transcript API**: For extracting video transcripts.

## **Installation**

1. Clone the Repository

    ```bash
    git clone https://github.com/yourusername/your-repository.git
    cd your-repository
    ```

2. Set Up a Virtual Environment (Optional but Recommended)

    Create a virtual environment to manage dependencies:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install Required Packages

    Install the necessary Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Set Up Environment Variables

    Create a `.env` file in the root directory and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key_here
    ```

## **Usage**

1. Run the Application

    Start the Streamlit application by running:

    ```bash
    streamlit run app.py
    ```

2. Enter a YouTube Video URL

    In the web interface, paste the YouTube video URL into the input field.

3. Get Detailed Notes

    Click the "Get Detailed Notes" button to process the video. The application will display the video thumbnail and generate a summary of the transcript.

## **Configuration**

- **Google API Key**: Ensure that you have set up your Google API key in the `.env` file.
- **Logo and Design**: Update the logo URL in the `app.py` file if needed and adjust the design elements in the custom CSS.

## **Example Files**

- **.env**: Contains environment variables such as the Google API key.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
