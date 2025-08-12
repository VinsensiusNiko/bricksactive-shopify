# Shopify https://www.bricksactive.id/ Project

## Deskripsi
Implementasi https://www.bricksactive.id/ pada theme Shopify Dawn.

## Fitur yang Dikerjakan
- Section Hero banner dengan video background.
    - video menggunakan link url youtube
    - button label dan link bisa disesuaikan
    - configuration dilakukan pada shopify editor admin   
- Section Product Category slider dengan tombol add-to-cart
    - memilih category/collection
    - title dan button bisa disesuaikan
    - configuration dilakukan pada shopify editor admin
    - masih ada bug pada ajax button add to cart, perlu pindah halaman/refresh halaman untuk update cart quantity
- Section Testimonial
    - tampilan css langsung dari code
    - value testimonial masih hardcode berupa format json, value testimonial diambil dari metadata. di edit dari Settings > Metafields and metaobjects > shop > Testimonials json > More action > edit value
    - modify layout homepage, desktop & responsive

## Tools & Teknologi
- Shopify Dawn theme
- css
- ajax

## Cara Menjalankan
1. Download atau clone repositori ini:
    git clone https://github.com/VinsensiusNiko/bricksactive-shopify.git
2. build pada local:
    shopify theme dev --store=https://md7q56-8a.myshopify.com/

## Link Demo
[Demo Store](https://md7q56-8a.myshopify.com/)
pass store: venom
