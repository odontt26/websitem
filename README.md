<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Kitap Dünyası</title>
<style>
  /* Reset ve Temel */
  * {
    box-sizing: border-box;
    margin: 0; padding: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  body {
    background: #f7f4ef;
    color: #333;
    line-height: 1.5;
  }
  a {
    text-decoration: none;
    color: #2c3e50;
  }
  a:hover {
    color: #e67e22;
  }
  .container {
    max-width: 1200px;
    margin: auto;
    padding: 0 20px;
  }
  /* Header */
  header {
    background: #2c3e50;
    color: white;
    padding: 15px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header .logo {
    font-size: 1.8rem;
    font-weight: bold;
    cursor: pointer;
  }
  nav ul {
    display: flex;
    list-style: none;
    gap: 20px;
  }
  nav ul li {
    padding: 6px 0;
  }
  nav ul li a {
    font-weight: 600;
    color: white;
    transition: color 0.3s;
  }
  nav ul li a:hover {
    color: #e67e22;
  }
  .search-bar {
    position: relative;
  }
  .search-bar input[type="search"] {
    padding: 6px 30px 6px 10px;
    border-radius: 15px;
    border: none;
    outline: none;
    font-size: 1rem;
  }
  .search-bar button {
    position: absolute;
    right: 5px;
    top: 50%;
    transform: translateY(-50%);
    background: transparent;
    border: none;
    cursor: pointer;
    color: #2c3e50;
    font-size: 1.1rem;
  }
  /* Hero */
  .hero {
    background: url('https://images.unsplash.com/photo-1512820790803-83ca734da794?auto=format&fit=crop&w=1400&q=80') no-repeat center/cover;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    padding: 0 20px;
    box-shadow: inset 0 0 0 1000px rgba(44,62,80,0.6);
  }
  .hero h1 {
    font-size: 3rem;
    margin-bottom: 15px;
    text-shadow: 2px 2px 6px rgba(0,0,0,0.7);
  }
  .hero p {
    font-size: 1.3rem;
    margin-bottom: 25px;
    max-width: 600px;
    text-shadow: 1px 1px 5px rgba(0,0,0,0.6);
  }
  .hero button {
    background: #e67e22;
    border: none;
    color: white;
    padding: 12px 30px;
    border-radius: 30px;
    font-size: 1.1rem;
    cursor: pointer;
    box-shadow: 0 5px 10px rgba(230,126,34,0.5);
    transition: background 0.3s;
  }
  .hero button:hover {
    background: #cf711c;
  }
  /* Kitap Kartları */
  .books-section {
    margin: 50px 0;
  }
  .section-title {
    text-align: center;
    color: #2c3e50;
    font-size: 2rem;
    margin-bottom: 30px;
    font-weight: 700;
  }
  .book-list {
    display: flex;
    gap: 25px;
    flex-wrap: wrap;
    justify-content: center;
  }
  .book-card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    width: 220px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }
  .book-card img {
    width: 100%;
    height: 320px;
    object-fit: cover;
  }
  .book-content {
    padding: 15px;
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .book-title {
    font-weight: 700;
    font-size: 1.1rem;
    margin-bottom: 8px;
    color: #34495e;
  }
  .book-author {
    font-style: italic;
    font-size: 0.9rem;
    color: #7f8c8d;
    margin-bottom: 12px;
  }
  .book-desc {
    font-size: 0.9rem;
    flex-grow: 1;
    color: #555;
    margin-bottom: 15px;
  }
  .book-price {
    font-weight: 700;
    color: #e67e22;
    font-size: 1.1rem;
    margin-bottom: 12px;
  }
  .book-card button {
    background: #e67e22;
    border: none;
    color: white;
    padding: 10px;
    border-radius: 8px;
    cursor: pointer;
    font-weight: 600;
    transition: background 0.3s;
  }
  .book-card button:hover {
    background: #cf711c;
  }
  /* Kategoriler */
  .categories {
    background: #ecf0f1;
    padding: 30px 20px;
    border-radius: 10px;
  }
  .categories-list {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
  }
  .category-item {
    background: white;
    padding: 15px 25px;
    border-radius: 25px;
    font-weight: 600;
    color: #2c3e50;
    cursor: pointer;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: background 0.3s, color 0.3s;
  }
  .category-item:hover, .category-item.active {
    background: #e67e22;
    color: white;
  }
  /* Blog Bölümü */
  .blog-section {
    margin: 50px 0;
  }
  .blog-posts {
    display: flex;
    gap: 25px;
    flex-wrap: wrap;
    justify-content: center;
  }
  .blog-post {
    background: white;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    width: 300px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }
  .blog-post img {
    width: 100%;
    height: 180px;
    object-fit: cover;
  }
  .blog-content {
    padding: 15px;
  }
  .blog-content h3 {
    font-size: 1.2rem;
    color: #2c3e50;
    margin-bottom: 10px;
  }
  .blog-content p {
    font-size: 0.95rem;
    color: #555;
    margin-bottom: 12px;
  }
  .blog-content a {
    font-weight: 600;
    color: #e67e22;
  }
  /* Newsletter */
  .newsletter {
    background: #2c3e50;
    color: white;
    padding: 40px 20px;
    text-align: center;
    border-radius: 10px;
    margin-bottom: 40px;
  }
  .newsletter input[type="email"] {
    padding: 12px 20px;
    width: 300px;
    max-width: 90%;
    border-radius: 30px 0 0 30px;
    border: none;
    font-size: 1rem;
    outline: none;
  }
  .newsletter button {
    padding: 12px 30px;
    border-radius: 0 30px 30px 0;
    border: none;
    background: #e67e22;
    color: white;
    font-weight: 700;
    cursor: pointer;
    transition: background 0.3s;
  }
  .newsletter button:hover {
    background: #cf711c;
  }
  /* Footer */
  footer {
    background: #1c2833;
    color: #ccc;
    text-align: center;
    padding: 20px 10px;
    font-size: 0.9rem;
  }
  footer a {
    color: #e67e22;
  }

  /* Responsive */
  @media(max-width: 768px){
    .book-list, .blog-posts {
      flex-direction: column;
      align-items: center;
    }
    nav ul {
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }
    header .container {
      flex-wrap: wrap;
      gap: 10px;
    }
  }
</style>
</head>
<body>

<!-- Header -->
<header>
  <div class="container">
    <div class="logo" onclick="window.location.reload()">Kitap Dünyası</div>
    <nav>
      <ul>
        <li><a href="#books">Kitaplar</a></li>
        <li><a href="#categories">Kategoriler</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#newsletter">Abone Ol</a></li>
      </ul>
    </nav>
    <div class="search-bar">
      <input type="search" id="searchInput" placeholder="Kitap ara..." oninput="searchBooks()" />
      <button onclick="searchBooks()">🔍</button>
    </div>
  </div>
</header>

<!-- Hero -->
<section class="hero">
  <h1>En Güzel Kitaplar Burada</h1>
  <p>Hayal dünyanıza açılan kapı. En yeni ve en popüler kitapları keşfedin.</p>
  <button onclick="scrollToSection('books')">Kitaplara Göz At</button>
</section>

<!-- Kitaplar -->
<section id="books" class="books-section container">
  <h2 class="section-title">Öne Çıkan Kitaplar</h2>
  <div class="book-list" id="bookList">
    <!-- Kitap kartları JS ile eklenecek -->
  </div>
</section>

<!-- Kategoriler -->
<section id="categories" class="categories container">
  <h2 class="section-title">Kategoriler</h2>
  <div class="categories-list" id="categoryList">
    <!-- Kategoriler JS ile eklenecek -->
  </div>
</section>

<!-- Blog -->
<section id="blog" class="blog-section container">
  <h2 class="section-title">Kitap Tavsiyeleri</h2>
  <div class="blog-posts" id="blogPosts">
    <!-- Blog yazıları JS ile eklenecek -->
  </div>
</section>

<!-- Newsletter -->
<section id="newsletter" class="newsletter">
  <h2>Haber Bültenimize Abone Olun</h2>
  <form onsubmit="subscribe(event)">
    <input type="email" id="emailInput" placeholder="Email adresinizi girin" required />
    <button type="submit">Abone Ol</button>
  </form>
  <p>Yeni çıkan kitaplar ve kampanyalardan ilk siz haberdar olun!</p>
</section>

<!-- Footer -->
<footer>
  <p>© 2025 Kitap Dünyası | <a href="mailto:iletisim@kitapdunyasi.com">iletisim@kitapdunyasi.com</a></p>
</footer>

<script>
  const books = [
    {
      title: "Sefiller",
      author: "Victor Hugo",
      desc: "Fransız yazar Victor Hugo'nun klasikleşmiş eseri, hayatın zorluklarını ve umudu anlatır.",
      price: "45₺",
      img: "https://images-na.ssl-images-amazon.com/images/I/81XJ1H0M64L.jpg",
      category: "Klasik"
    },
    {
      title: "Simyacı",
      author: "Paulo Coelho",
      desc: "Kişisel efsanenizi keşfetme yolunda sihirli bir hikaye.",
      price: "38₺",
      img: "https://cdn.kitapambari.com/2020/01/Paulo-Coelho-Simyaci.jpg",
      category: "Felsefe"
    },
    {
      title: "Harry Potter ve Felsefe Taşı",
      author: "J.K. Rowling",
      desc: "Harry Potter serisinin ilk kitabı, büyü ve macera dolu dünyaya giriş.",
      price: "60₺",
      img: "https://cdn.dribbble.com/users/1078340/screenshots/3135214/harrypotter.png",
      category: "Fantastik"
    },
    {
      title: "Kürk Mantolu Madonna",
      author: "Sabahattin Ali",
      desc: "Tutkulu ve hüzünlü bir aşk hikayesi.",
      price: "30₺",
      img: "https://cdn.kitapambari.com/2017/06/Kürk-Mantolu-Madonna.jpg",
      category: "Roman"
    },
    {
      title: "1984",
      author: "George Orwell",
      desc: "Distopik bir gelecekte totaliter rejimin korkunç portresi.",
      price: "42₺",
      img: "https://cdn.dribbble.com/users/1234567/screenshots/7654321/1984-book-cover.png",
      category: "Bilim Kurgu"
    }
  ];

  const categories = [...new Set(books.map(book => book.category))];

  const blogs = [
    {
      title: "2025'in En Çok Okunan Kitapları",
      desc: "Bu yıl en çok satan ve beğenilen kitapları keşfedin.",
      img: "https://images.unsplash.com/photo-1516972810927-80185027ca84?auto=format&fit=crop&w=600&q=80"
    },
    {
      title: "Okuma Alışkanlığınızı Artırmanın Yolları",
      desc: "Günlük hayatınıza kitap okumayı nasıl entegre edebilirsiniz?",
      img: "https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?auto=format&fit=crop&w=600&q=80"
    },
    {
      title: "Klasik Edebiyatın Büyüsü",
      desc: "Neden klasik kitaplar hala vazgeçilmezdir?",
      img: "https://images.unsplash.com/photo-1507842217343-583bb7270b66?auto=format&fit=crop&w=600&q=80"
    }
  ];

  // Kitapları göster
  const bookList = document.getElementById('bookList');
  function displayBooks(list) {
    bookList.innerHTML = '';
    if(list.length === 0){
      bookList.innerHTML = '<p style="text-align:center; width:100%;">Aradığınız kriterlerde kitap bulunamadı.</p>';
      return;
    }
    list.forEach(book => {
      const card = document.createElement('div');
      card.className = 'book-card';
      card.innerHTML = `
        <img src="${book.img}" alt="${book.title}" />
        <div class="book-content">
          <div class="book-title">${book.title}</div>
          <div class="book-author">by ${book.author}</div>
          <div class="book-desc">${book.desc}</div>
          <div class="book-price">${book.price}</div>
          <button onclick="alert('Sepete eklendi: ${book.title}')">Sepete Ekle</button>
        </div>
      `;
      bookList.appendChild(card);
    });
  }
  displayBooks(books);

  // Kategorileri göster
  const categoryList = document.getElementById('categoryList');
  function displayCategories(){
    categories.forEach(cat => {
      const catDiv = document.createElement('div');
      catDiv.className = 'category-item';
      catDiv.textContent = cat;
      catDiv.onclick = () => {
        document.querySelectorAll('.category-item').forEach(i => i.classList.remove('active'));
        catDiv.classList.add('active');
        if(cat === 'Tümü'){
          displayBooks(books);
        } else {
          displayBooks(books.filter(b => b.category === cat));
        }
      }
      categoryList.appendChild(catDiv);
    });
    // "Tümü" butonunu başa ekle
    const allBtn = document.createElement('div');
    allBtn.className = 'category-item active';
    allBtn.textContent = 'Tümü';
    allBtn.onclick = () => {
      document.querySelectorAll('.category-item').forEach(i => i.classList.remove('active'));
      allBtn.classList.add('active');
      displayBooks(books);
    }
    categoryList.prepend
