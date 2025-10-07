# AI-Powered Study Buddy 📚

An intelligent study companion built with Streamlit and Google Gemini AI that helps students learn more effectively through AI-powered explanations, summaries, quizzes, and flashcards.

## Features

- **📘 Explain Concept**: Get simple, easy-to-understand explanations of any topic
- **📝 Summarize Notes**: Transform lengthy notes into concise summaries
- **❓ Generate Quiz**: Create multiple choice, true/false, and short-answer questions
- **🎴 Flashcards**: Interactive flip cards for effective memorization
- **📥 Export**: Download quizzes and flashcards as text or CSV files
- **📱 Mobile-Friendly**: Responsive design that works on all devices

## Setup Instructions

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Get Google Gemini API Key

1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy the API key

### 3. Configure Environment

1. Create a `.env` file in the project root:
```bash
GEMINI_API_KEY=your_actual_api_key_here
```

### 4. Run the Application

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`

## Usage

1. **Explain Concept**: Enter any topic and get a simple explanation
2. **Summarize Notes**: Paste your notes for a concise summary
3. **Generate Quiz**: Create quizzes from your study material
4. **Flashcards**: Generate interactive flashcards for memorization

## Tech Stack

- **Frontend**: Streamlit
- **AI**: Google Gemini API
- **Data Processing**: Pandas
- **Styling**: Custom CSS with modern UI components

## Features in Detail

### Explain Concept
- Simple explanations with analogies
- Easy-to-understand language
- Comprehensive coverage

### Summarize Notes
- Adjustable summary length
- Key point extraction
- Clear, concise output

### Generate Quiz
- Multiple question types (MCQ, True/False, Short Answer)
- Customizable number of questions
- Answer explanations
- Download as text file

### Flashcards
- Interactive flip animation
- Front/back card design
- Download as text or CSV
- Mobile-friendly interface

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.
