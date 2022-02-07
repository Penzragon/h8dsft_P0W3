# Hacktiv8 Phase 0: Graded Challenge 3

Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada Practical Statistics.

---

By [Rifky Aliffa](https://github.com/Penzragon)

![Kickstarter](https://logos-world.net/wp-content/uploads/2020/10/Kickstarter-Logo.png)

## Dataset

Data yang digunakan adalah dataset yang berisi project yang dikumpulkan dari [Kickstarter Platform](https://www.kickstarter.com/). Dataset dapat dilihat di [Kaggle](https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv).

Kolom pada dataset cukup jelas, kecuali beberapa kolom berikut:

- usd pledged: hasil konversi dari kolom `pledged` dalam bentuk USD (konversi dilakukan oleh [Kickstarter](https://www.kickstarter.com/))
- usd_pledged_real: hasil konversi dari kolom `pledged` dalam bentuk USD (konversi dari [Fixer.io API](https://fixer.io/))
- usd_goal_real: hasil konversi dari kolom `goal` dalam bentuk USD (konversi dari [Fixer.io API](https://fixer.io/))

## Objective

Tujuan yang ingin dicapai dalam project ini adalah untuk mengetahui apakah kategori sebuah project mempengaruhi kesuksesannya dengan menggunakan dataset yang ada.
