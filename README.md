# Dr. Saeed Psychiatry Clinic — Website Files

## Folder Structure (rakhein bilkul isi tarah)

```
/
├── index.html                          (homepage)
├── 404.html                            (error page)
├── robots.txt
├── sitemap.xml
├── about-dr-muhammad-saeed-khan.html
├── assets/
│   ├── logo.png                        (site logo)
│   ├── style.css                       (main design/CSS - shared by ALL pages)
│   └── subpages.css                    (extra CSS for sub-pages)
├── conditions/                         (27 condition/treatment pages)
├── articles/                           (8 patient education articles)
├── guides/                             (3 AEO/comparison guide pages)
└── locations/
    └── dir-timergara-psychiatrist.html
```

## ⚠️ Zaroori

- **`assets/` folder zaroor sath upload/push karein** — isme CSS aur logo hai. Iske bina koi bhi page unstyled/plain dikhega.
- Sab folders (`conditions/`, `articles/`, `guides/`, `locations/`, `assets/`) **root ke sath usi level pe** honi chahiye jaise upar dikhaya gaya hai — sub-folder mat banayein.

## GitHub push karne ka tareeqa

```bash
git init
git add .
git commit -m "Website update: SEO/AEO/GEO optimization, 42 pages, new logo"
git branch -M main
git remote add origin <aapka-repo-url>
git push -u origin main
```

## Hosting pe deploy karne ke baad

1. Google Search Console mein `sitemap.xml` dobara submit karein
2. Naye pages ke liye "Request Indexing" karein
3. Website ko browser mein khol kar check karein ke CSS/logo sahi load ho raha hai
