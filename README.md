# AI Text Summarizer App

Welcome to the GitHub repository for the AI Text Summarizer App! This project utilizes Express.js for the backend, Hugging Face API for AI text summarization, and HTML/CSS/JavaScript for the frontend. This document will guide you through setting up the project and getting started.

## Prerequisites

Before getting started, ensure you have the following installed:

- Node.js and npm (Node Package Manager)
- Git (for cloning the repository)

## Setup Instructions

1. **Clone the Repository:**
   ```
   git clone https://github.com/mohdamaan069/AI-Text-Summarizer-App.git
   ```

2. **Navigate to the Project Directory:**
   ```
   cd AI-Text-Summarizer-App
   ```

3. **Install Dependencies:**
   ```
   npm install
   ```

4. **Get Hugging Face API Access Token:**
   - Sign up for an account at [Hugging Face](https://huggingface.co/join).
   - Retrieve your API access token from your account settings.

5. **Set Up Environment Variables:**
   - Create a `.env` file in the project root.
   - Add the following content to the `.env` file:
     ```
     HUGGINGFACE_API_TOKEN=your-api-token
     ```
     Replace `your-api-token` with the token you obtained from Hugging Face.

6. **Start the Development Server:**
   ```
   npm start
   ```

7. **Access the Application:**
   Open your web browser and go to `http://localhost:3000` to access the AI Text Summarizer App.

## Folder Structure

The project structure is organized as follows:

- `public/` - Contains static assets like HTML, CSS, and client-side JavaScript files.
- `index.js` - Entry point of the application.
- `summarize.js` - Calls API and accept responses.

## Contributing

Contributions are welcome! If you have any ideas for improvements or find any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Now you're all set to start working on the AI Text Summarizer App! If you have any questions or need further assistance, don't hesitate to reach out. Happy coding! 🚀

Live link: https://ai-text-summarizer-app-amaan.vercel.app/
