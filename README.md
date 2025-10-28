🛍️ Product Catalogue with Filters
An interactive Product Catalogue web app built using HTML, CSS, and JavaScript that allows users to filter products dynamically by category and price range.
This project demonstrates client-side interactivity, DOM manipulation, and responsive design principles.

🚀 Live Demo
🔗 View Project Online
(Add your GitHub Pages or Netlify link here once deployed)

📸 Preview
deployment link:https://julie03042006.github.io/Product-catalog/
repository link:https://github.com/julie03042006/Product-catalog.git

![Product Catalogue Screenshot](https://via.placeholder.com/800x400?text=Product+Catalogue+Preview)
✨ Features
🧭 Dynamic Filtering — Filter products by category (e.g., Electronics, Clothing, Home).

💸 Price Range Filter — Adjust a range slider to filter products within your budget.

⚡ Instant Updates — Filters apply instantly without reloading the page.

📱 Responsive Design — Works seamlessly across desktop and mobile devices.

🎨 Modern UI — Clean and minimal layout with smooth hover effects.

🛠️ Built With
Technology	Purpose
HTML5	Structure and layout
CSS3	Styling and responsive design
JavaScript (ES6)	Logic, interactivity, and DOM manipulation
📂 Folder Structure
product-catalogue/
│
├── index.html        # Main HTML file
├── style.css         # Styling (if separated)
├── script.js         # JavaScript logic (if separated)
└── assets/           # (Optional) images and media
⚙️ How to Use
Clone the repository

git clone https://github.com/your-username/product-catalogue-with-filters.git
Navigate to the project folder

cd product-catalogue-with-filters
Open the app
Simply open index.html in your browser.

🧩 Key Functionalities
🔹 Filter by Category
Users can select one or more categories (e.g., Electronics, Clothing, Home) to view relevant products only.

🔹 Filter by Price
Use the range slider to limit products under a selected maximum price.

🔹 Real-Time Rendering
All filters apply instantly — no page reloads, thanks to JavaScript event listeners.

💡 Example Code Snippet
function applyFilters() {
  const selectedCategories = Array.from(document.querySelectorAll('.category-filter'))
    .filter(cb => cb.checked)
    .map(cb => cb.value);

  const maxPrice = parseInt(document.getElementById('priceRange').value);

  const filtered = products.filter(p => {
    const inCategory = selectedCategories.length === 0 || selectedCategories.includes(p.category);
    const inPrice = p.price <= maxPrice;
    return inCategory && inPrice;
  });

  renderProducts(filtered);
}
🌐 Deployment
You can easily deploy this project using GitHub Pages:

Push your code to GitHub.

Go to your repository’s Settings → Pages.

Under Branch, select main and / (root) folder.

Click Save — your app will be live at:
https://your-username.github.io/product-catalogue-with-filters/

🙌 Future Enhancements
🔍 Add a search bar to filter by product name.

🏷️ Include sorting options (e.g., by price or popularity).

🛒 Add a shopping cart or “add to favorites” feature.

🌙 Dark mode toggle.

