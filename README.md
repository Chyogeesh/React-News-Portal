# React-News-Portal
It is a internship assignment
To develop the React News Portal as described, we'll break down the tasks and provide a simple implementation using functional components, React hooks, Redux Toolkit for state management, and integration with a public news API (specifically using NewsAPI).

Step-by-Step Implementation
1. Project Setup
First, ensure you have Node.js installed on your machine. Then, create a new React application using Create React App:
Structure and Components
Organize your project structure:

src/
components/
Article.js: Component to display each article.
ArticleDetail.js: Component for detailed view of an article.
CategoryFilter.js: Component for filtering articles by category.
Pagination.js: Component for pagination of articles.
Loader.js: Component for loading state during API calls.
pages/
Home.js: Homepage displaying articles.
ArticlePage.js: Detailed view of an article.
redux/
store.js: Redux store configuration.
slices/
articlesSlice.js: Redux slice for managing articles state.
