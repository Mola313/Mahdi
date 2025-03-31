<!DOCTYPE html><html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدونتي</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; direction: rtl; }
        .navbar { background-color: #333; padding: 10px; }
        .navbar a { color: white; text-decoration: none; padding: 10px; display: inline-block; }
        .content { display: none; padding: 20px; }
        .active { display: block; }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="#" onclick="showSection('library')">المكتبة</a>
        <a href="#" onclick="showSection('scholars')">علماؤنا</a>
        <a href="#" onclick="showSection('doubts')">شبهات</a>
        <a href="#" onclick="showSection('doubts')">فريق بزوغ الإمام المهدي</a>
        
    </div>
    <div id="library" class="content active">
        <h2>المكتبة</h2>
        <p>هنا ستجد مجموعة من الكتب والمقالات المفيدة
        #5582ff.</p>
    </div>
    <div id="scholars" class="content">
        <h2>علماؤنا</h2>
        <p>الإمام الخميني (1902-1989) هو روح الله الموسوي الخميني، قائد الثورة الإسلامية في إيران عام 1979 ومؤسس الجمهورية الإسلامية. ولد في مدينة خمين بإيران، ودرس العلوم الدينية في حوزة قم، وأصبح مرجعاً دينياً بارزاً. عُرف بمعارضته الشديدة لحكم الشاه محمد رضا بهلوي، مما أدى إلى نفيه عام 1964. قاد الثورة من المنفى حتى عودته عام 1979 وإسقاط نظام الشاه. شغل منصب القائد الأعلى للجمهورية الإسلامية حتى وفاته. ترك إرثاً فكرياً وسياسياً كبيراً في إيران والعالم الإسلامي</p>. 
        <p>تعرف على أبرز العلماء وإنجازاتهم.</p>
    </div>
    <div id="doubts" class="content">
        <h2>شبهات</h2>
        <p>الردود على الشبهات المتداولة.</p>
    </div>
    <script>
        function showSection(sectionId) {
            document.querySelectorAll('.content').forEach(div => div.classList.remove('active'));
            document.getElementById(sectionId).classList.add('active');
        }
    </script>
</body>
</html>
