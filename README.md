<h1>News Aggregator App</h1>

<p>This app is an Android-based news aggregator that fetches and displays current news articles from a wide variety of news sources. Users can browse through different news categories and view top stories from selected sources. Built using <strong>Android Studio</strong> and <strong>Java</strong>, it integrates with <a href="https://newsapi.org/">NewsAPI.org</a> for news sources and articles.</p>

<h2>Features</h2>
<ul>
  <li>Displays news from a variety of sources (e.g., CNN, BBC, etc.) covering different news categories (e.g., sports, politics, technology).</li>
  <li>Selecting a news source shows up to 10 top stories from that source.</li>
  <li>Users can filter news sources by topic (e.g., tech, sports), showing only relevant sources for that topic.</li>
  <li>Swipe through news articles using <strong>ViewPager2</strong>: swipe right for the next article and left to go back to the previous article.</li>
  <li>Click on the article's title, text, or image to open the full article on the news source’s website.</li>
  <li>Uses <strong>Drawer Layout</strong> for easy navigation between different news categories and sources.</li>
  <li>Professional launcher icon added for a polished look.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Android Studio</strong> - Development environment.</li>
  <li><strong>Java</strong> - Programming language.</li>
  <li><strong>NewsAPI.org</strong> - API to fetch news articles and sources.</li>
  <li><strong>Android Volley</strong> - For making API requests and handling JSON data.</li>
  <li><strong>View Binding</strong> - Used throughout the app for better view management (no <code>findViewById</code>).</li>
  <li><strong>ViewPager2</strong> - For swiping between news articles.</li>
  <li><strong>Drawer Layout</strong> - For navigation between categories and sources.</li>
  <li><strong>Adapters</strong> - For handling data in lists and views.</li>
  <li><strong>Dynamic Menus</strong> - For flexible news source and category selection.</li>
  <li><strong>Implied Intents</strong> - For opening news articles in a browser.</li>
</ul>

<h2>How to Run</h2>
<ol>
  <li>Clone the repository:
    <pre><code>https://github.com/RikGanguli/Android-News-Aggregator.git</code></pre>
  </li>
  <li>Open the project in Android Studio.</li>
  <li>Ensure you have the required dependencies in your <code>build.gradle</code> file (e.g., Android Volley, ViewPager2, etc.).</li>
  <li>Run the app on an Android device or emulator.</li>
</ol>

<h2>API Setup</h2>
<ol>
  <li>Sign up for an API key from <a href="https://newsapi.org/">NewsAPI.org</a>.</li>
  <li>Insert your API key at the appropriate location in MainActivity.java.</li>
</ol>

<h2>Usage</h2>
<ul>
  <li>On launch, the app shows a variety of news categories (e.g., sports, tech).</li>
  <li>Select a category to filter news sources.</li>
  <li>Select a news source to view the top stories.</li>
  <li>Swipe through articles using the ViewPager2.</li>
  <li>Click on an article's title or image to view the full article in a browser.</li>
</ul>

<h2>Screenshots</h2>
<p>(Add screenshots of your app here)</p>

<h2>Credits</h2>
<p>Developed by Rik Ganguli Biswas</p>
<p>Powered by <a href="https://newsapi.org/">NewsAPI.org</a></p>
