# BDR AUTO SERVICE

Tek dosyalık oto servis yönetim uygulaması (`public/index.html`).

## GitHub'a yükleme
    git init
    git add .
    git commit -m "ilk sürüm"
    git branch -M main
    git remote add origin https://github.com/KULLANICI_ADI/bdr-auto-service.git
    git push -u origin main

## Firebase Hosting'e yayınlama
    npm install -g firebase-tools
    firebase login
    firebase use --add      # projeni seç
    firebase deploy --only hosting

## Güncelleme
`public/index.html` dosyasını değiştir, sonra:

    git add . && git commit -m "güncelleme" && git push
    firebase deploy --only hosting

Not: Veriler her cihazın tarayıcısında (localStorage) saklanır. Adres değişince veya
başka cihaza geçince Özet ekranındaki Yedek / Geri yükle ile veriyi taşı.
