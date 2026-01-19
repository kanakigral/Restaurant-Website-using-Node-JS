# 🍰 Dynamic Restaurant Website (Node.js)

A dynamic restaurant/dessert website built using **Node.js**, **HTML**, **CSS**, and **server-side templating**.
This project displays products dynamically, shows detailed product pages, and demonstrates how Node.js can be used to render HTML templates with real data.

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/kanakigral/your-repo-name.git
   ```

2. Go to the project folder:

   ```bash
   cd your-repo-name
   ```

3. Run the server:

   ```bash
   node index.js
   ```

4. Open your browser and visit:

   ```
   http://localhost:8000
   ```


---

## 🚀 Features

* Dynamic product listing page
* Individual product detail pages
* Server-side rendering using Node.js
* Reusable HTML templates
* Simple routing without any framework
* Clean and responsive UI design
* Easy to extend with more products or features

---

## 🛠️ Technologies Used

* **Node.js**
* **HTML5**
* **CSS3**
* **JavaScript**
* **File System (fs module)**
* **HTTP module**

---

## 📄 Templates Explanation

* **template-overview.html**
  Displays the homepage with all products listed dynamically.

* **template-card.html**
  Reusable card component used to display each product in the overview page.

* **template-product.html**
  Displays detailed information about a selected product using query parameters.

---

## ⚙️ How It Works

1. Node.js reads product data from a JSON file.
2. HTML templates contain placeholders like `{%PRODUCTNAME%}`, `{%PRICE%}`, etc.
3. These placeholders are replaced dynamically using JavaScript.
4. Routes:

   * `/overview` → Shows all products
   * `/product?id=0` → Shows individual product details
