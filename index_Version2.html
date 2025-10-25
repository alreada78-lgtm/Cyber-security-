<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>مكتبة إلكترونية حديثة</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@500;700&display=swap');
    body {
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(120deg, #f7fafc 0%, #e3e6e8 100%);
      margin: 0;
      padding: 0;
      color: #222;
    }
    header {
      background: linear-gradient(90deg, #4e54c8, #8f94fb);
      color: #fff;
      padding: 30px 0 20px 0;
      text-align: center;
      box-shadow: 0 2px 8px #e3e6e8;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 25px;
      margin: 20px 0 10px 0;
    }
    nav button {
      background: #fff;
      color: #4e54c8;
      border: none;
      border-radius: 30px;
      padding: 10px 28px;
      font-size: 1.1rem;
      cursor: pointer;
      font-weight: 700;
      transition: background 0.2s, color 0.2s;
    }
    nav button.active, nav button:hover {
      background: #4e54c8;
      color: #fff;
    }
    .search-box {
      display: flex;
      justify-content: center;
      margin: 25px 0 15px 0;
    }
    .search-box input {
      width: 340px;
      padding: 12px 18px;
      border-radius: 30px;
      border: 1.5px solid #8f94fb;
      font-size: 1rem;
      outline: none;
      transition: border 0.2s;
    }
    .search-box input:focus {
      border: 2.5px solid #4e54c8;
    }
    .books-section {
      max-width: 1140px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 28px;
      padding: 30px 20px;
    }
    .book-card {
      background: #fff;
      border-radius: 22px;
      box-shadow: 0 3px 12px #e3e6e8b3;
      padding: 25px 18px 22px 18px;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .book-card:hover {
      transform: translateY(-6px) scale(1.03);
      box-shadow: 0 6px 24px #4e54c830;
    }
    .book-card h3 {
      margin: 0 0 8px 0;
      color: #4e54c8;
      font-size: 1.15rem;
    }
    .book-card .category {
      background: #e8e8fc;
      color: #4e54c8;
      padding: 4px 16px;
      border-radius: 12px;
      font-size: 0.95rem;
      margin-bottom: 7px;
    }
    .book-card p {
      margin: 0;
      color: #555;
      font-size: 0.98rem;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 1.5rem;}
      nav { gap: 10px;}
      .search-box input { width: 95vw;}
      .books-section { grid-template-columns: 1fr;}
    }
  </style>
</head>
<body>
  <header>
    <h1>مكتبة إلكترونية حديثة</h1>
    <nav>
      <button class="active" data-category="all">الكل</button>
      <button data-category="عام">كتب عامة</button>
      <button data-category="ديني">كتب دينية</button>
      <button data-category="فلسفي">كتب فلسفية</button>
      <button data-category="علمي">كتب علمية</button>
    </nav>
    <div class="search-box">
      <input type="text" id="searchInput" placeholder="ابحث عن كتاب...">
    </div>
  </header>
  <main>
    <section class="books-section" id="booksSection">
      <!-- سيتم عرض الكتب هنا -->
    </section>
  </main>
  <script>
    // بيانات الكتب الافتراضية
    const books = [
      { title: "العادات السبع للناس الأكثر فعالية", desc: "كتاب تطوير ذاتي يقدم استراتيجيات للنجاح في الحياة.", category: "عام" },
      { title: "البداية والنهاية", desc: "كتاب تاريخي وديني شهير لابن كثير.", category: "ديني" },
      { title: "تأملات", desc: "كتاب فلسفي عميق للإمبراطور ماركوس أوريليوس.", category: "فلسفي" },
      { title: "العلم وأزمة الضمير الحديث", desc: "كتاب يناقش العلاقة بين العلم والأخلاق.", category: "علمي" },
      { title: "نظرية الفستق", desc: "كتاب تنمية ذاتية مشهور.", category: "عام" },
      { title: "رياض الصالحين", desc: "مجموعة من الأحاديث النبوية الشريفة.", category: "ديني" },
      { title: "الجمهورية", desc: "تحفة فلسفية لأفلاطون حول العدالة والمجتمع.", category: "فلسفي" },
      { title: "تاريخ العلم", desc: "كتاب يستعرض تطور العلوم عبر العصور.", category: "علمي" },
      { title: "في ظلال القرآن", desc: "تفسير معاصر للقرآن الكريم لسيد قطب.", category: "ديني" },
    ];

    const booksSection = document.getElementById('booksSection');
    const navBtns = document.querySelectorAll('nav button');
    const searchInput = document.getElementById('searchInput');

    function renderBooks(bookList) {
      booksSection.innerHTML = '';
      if (!bookList.length) {
        booksSection.innerHTML = `<div style="text-align:center;width:100%;color:#888;font-size:1.2rem;">لا توجد كتب مطابقة</div>`;
        return;
      }
      bookList.forEach(book => {
        const card = document.createElement('div');
        card.className = 'book-card';
        card.innerHTML = `
          <span class="category">${book.category}</span>
          <h3>${book.title}</h3>
          <p>${book.desc}</p>
        `;
        booksSection.appendChild(card);
      });
    }

    // تصفية حسب القسم
    navBtns.forEach(btn => {
      btn.onclick = () => {
        navBtns.forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        const cat = btn.dataset.category;
        const filtered = cat === 'all' ? books : books.filter(b => b.category === cat);
        const searchValue = searchInput.value.trim();
        if (searchValue) {
          renderBooks(filtered.filter(b => b.title.includes(searchValue) || b.desc.includes(searchValue)));
        } else {
          renderBooks(filtered);
        }
      };
    });

    // البحث
    searchInput.addEventListener('input', () => {
      const value = searchInput.value.trim();
      const cat = document.querySelector('nav button.active').dataset.category;
      let filtered = cat === 'all' ? books : books.filter(b => b.category === cat);
      if (value) {
        filtered = filtered.filter(b => b.title.includes(value) || b.desc.includes(value));
      }
      renderBooks(filtered);
    });

    // عرض جميع الكتب عند التحميل
    renderBooks(books);
  </script>
</body>
</html>