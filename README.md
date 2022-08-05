# Project2_2022

PROJECT2022NEW PROJEMİN KONUSU NEDİR?

Bu projede verimde bulunana tüm tweetleri (yorumları) duygu analizlerini yaparak birbirinden ayırt edilmesi üzerinde çalıştım. Data verilerimi metin şeklinde excel dosyası üzerinden temin ettim. Kodlamış olduğum yazılımımda farklı farklı verileri içeren kelimelerden cümle analizi yaparak hangi cümlenin pozitif hangisinin negatif ve nötr olduğunun ayırt edilmesini görebilirsiniz. 

PROJEDE KULLANILAN PROGRAMLAMA DİLLERİ VE MODELLER

Projemde kullanmış olduğum programlama dil olarak Python’u seçtim, çünkü yapay zeka alanında bir proje üzerinde çalışırken diğer programlama dillerine oranla daha fazla yardım sağlayabileceği metodlar ve kütüphaneler var. Ek olarak, ntlk, nlp, naive bayes gibi daha birçok özelliklere de projemde yer verdim.

PROJE HAKKINDA

Projemi özetlemem gerekirse, öncelikle buraya yüklemiş olduğum yazılım birçok kaynaktan araştırılarak hem de kendi bilgilerimle sentezlenerek yapılmış farklı yolları içeren bir yazılım. Bunun yanı sıra temel amacı tüm kodlama çeşitlerinde hep aynı olduğu için – tweets sentiment analysis / yorumlarda duygu analizi- projemdeki hangi yazılımı seçerseniz seçin doğru sonuca sizin de birkaç ekleyeceğiniz kodlama ile birlikte rahatlıkla ulaşabileceğinizi gözlemleyebilirsiniz.

NOT: Yorum satırlarına almış olduğum farklı yolları oluşturmaktadır. Her iki yöntemle de doğru sonuca doğru bir şekilde ulaşabilirsiniz.

Projede ilk olarak bahsetmem gereken en önemli şeylerden biri Kaggle ile Google Collabı bağlamış olmam zaten bu kodlamaları direkt projemi açtığınızda görebilirsiniz. Daha sonra, datayı kaggledan aldığım için train ve test verilerim oldu.  Ardından her adımımda tablo oluşturarak ilerlemeyi tercih ettim ki, daha rahat anlaşılabilir bir yazılım elde edebileyim. İlk olarak, textID, text ve selected_text, sentiment in olduğu bir tablo oluşturdum. Bu şekilde, hangi kullanıcının hangi yorumu yaptığını ve bu yorumdan hangi kelimenin veya kelimelerin bizim hangi duygu sınıflamasına girdiğini gözlemledim. Bu şekilde, verimde kaç tane pozitif, kaç tane negatif ve kaç tane nötr yorum var bunları rahatlıkla gördüm. Ek olarak, kaç kelimeden tüm veri boyunca kaç tane olduğunu gözlemledim her bir duygu için. (pozitif, negatif, nötr) Ardından, yeni nötr, pozitif, negatif kelimeler oluşturdum ve train & test yaparak bir sonraki kelime veya cümlenin analiz edilmesini sağladım. Burada, kelimeler oluştururken ingilizce kelimeler oluşturdum. Bunun için farklı kodlamalardan yararlandım ( spacy language). Ek olarak, dil öğrenmesini nlp ile kodladım. En sonda ise kaç tane pozitif kaç tane negatif yorum olduğunu tablo şeklinde bastım ve tekrar yeni oluşturulan kelimeler ile birlikte cümlelerin duygu analizinin sonucunu tablo şeklinde gösterdim.

İyi çalışmalar…
