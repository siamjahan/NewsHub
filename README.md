# **NewsHub**
A responsive react web application that delivers the latest news articles by leveraging API calls.


## **Key Features**
- **Category-based News Feed**: Displays the latest news articles categorized by different topics like Technology, Business, Health, Sports, and Entertainment.
- **News Details**: Each news article includes a title, description, an image (if available), and a link to the full article.
- **Error Handling**: Displays a fallback message when there is no description for an article.
- **Customizable News Categories**: Users can toggle between different categories of news with ease.
- **Live Data Fetching**: The app fetches real-time data from the News API.



## **Technologies Used**

- **React.js**: A JavaScript library for building user interfaces.
- **Bootstrap 5**: A front-end framework for responsive design and UI components.
- **News API**: A service to fetch the latest news articles from various sources.
- **Vite**: A fast build tool and development server for modern web applications.


## **Installation**

Follow these steps to set up the project locally:

### 1. **Clone the Repository**
Clone the project to your local machine using the following command:
```bash
git clone https://github.com/siamjahan/NewsHub.git
```

### 2. **Navigate to the Project Directory**
Once cloned, navigate to the project directory:
```bash
cd NewsHub
```

### 3. **Install Dependencies**
Install the required dependencies using npm:
```bash
npm install
```

### 4.**Set Up API Key**
To fetch the news data, you'll need an API key from News API. For security reasons, the API key is not stored directly in the source code. Instead, it is stored in an environment variable, which is loaded from a .env file.

Go to the News API website and create an account.
After signing in, generate an API key.
Create a .env file in the root directory of your project and add your API key like this:
```bash
VITE_API_KEY=your-api-key-here
```

### 5.**Run the Application**
To start the development server and view the app locally, run the following command:
```bash
npm run dev
```












