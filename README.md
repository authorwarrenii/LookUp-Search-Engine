LookUp-Search-Engine
A minimalist, privacy-focused search page that handles custom data indexing completely client-side. Inspired by Albert Einstein's famous quote: "Never memorize what you can look up."

🚀 Overview
LookUp is a fast, lightweight search engine alternative designed to declutter your workflow and save your brainpower. It skips external databases and complex backends entirely, utilizing an optimized client-side JavaScript architecture to filter through targeted collections of documentation, links, and text references instantaneously.

✨ Key Features
Zero-Backend Architecture: Runs completely inside the browser using clean HTML5, CSS3, and native vanilla JavaScript.
Real-Time Filtering: Executes functional queries instantly using an oninput event listener to evaluate matching titles and descriptions as you type.
Sleek Dark Mode: Designed with a customized, eye-strain-free material dark aesthetic utilizing iconic multi-colored branding layers.
Privacy-First Approach: Local filtering logic means search inputs stay contained inside your browser window without third-party data tracking.

🛠️ How It Works
The engine relies on a localized array structure containing pre-indexed data objects:

const webPages = [
    { 
        title: "The Power of Intrinsic Motivation", 
        url: "https://example.com", 
        desc: "Learn how internal drive and passion beat external rewards..." 
    }
];

The system automatically normalizes query string variables to lower case, evaluates truthy values across database attributes, and dynamically constructs atomic document fragments inside the DOM wrapper.
📦 Local Deployment
To run this application locally without needing web servers:
   1. Clone the repository or download the source code.
   2. Save the markup document file locally as index.html.
   3. Double-click the file to launch it directly inside any standard desktop or mobile web browser.
