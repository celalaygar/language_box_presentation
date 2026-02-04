# language_box_presentation


🇬🇧🌍 Introducing Lingua Bubble – A Fun Way to Learn Languages!

We've developed a multilingual mobile app called Lingua Bubble, which offers an AI-powered, game-based language learning experience! It's now available in beta.
We’ve just launched Lingua Bubble, a multilingual mobile app designed to make language learning engaging and
interactive.
Now available on iOS and Android, Lingua Bubble supports 9 different languages:
🇬🇧 English | 🇩🇪 German | 🇹🇷 Turkish | 🇮🇹 Italian | 🇵🇹 Portuguese | 🇫🇷 French | 🇷🇺 Russian | 🇪🇸 Spanish | 🇰🇷 Korean

Once you select a language and your level (A1–C2), you can explore 5 fun learning games:

🎯 Scrambled Word – Unscramble the letters to find the right word.
✍️ Sentence Completion – Fill in the missing word using scrambled hints.
🧩 Sentence Builder – Reorder words to form correct sentences.
🎤 Speech Game – Listen to sentences and find the missing word by ear.
🔊 Voice Match – Listen and match the correct spoken sentence from multiple options.

Each game helps you improve vocabulary, comprehension, and pronunciation in a playful way.

📥 Download Lingua Bubble now:
➡️ Play Store: https://lnkd.in/d6YjUZeV
➡️ App Store: https://lnkd.in/dZzttbQe


🌟 Coming soon:
🧠 Puzzle-based learning modules
🗣️ An AI-powered animated character for interactive speaking practice

Discover more on our project page:
👉 https://lnkd.in/dU2RJvWs

💬 I’d love to hear your thoughts — which feature would you try first?
hashtag#LinguaBubble hashtag#LanguageLearning hashtag#MobileApp hashtag#EdTech hashtag#iOS hashtag#Android hashtag#GamifiedLearning hashtag#LearnLanguages hashtag#SpeechGame hashtag#AIlearning hashtag#TechInnovation
hashtag#improve hashtag#improvement hashtag#learning hashtag#language hashtag#languages hashtag#speech hashtag#pronunciation hashtag#vocabulary hashtag#education hashtag#funlearning
hashtag#languageapp hashtag#learningapp hashtag#mobilelearning hashtag#languagepractice





#  About Language Box

English Explanation 

This is a Flutter-based mobile application designed for language learning. It offers a collection of interactive, game-like exercises to help users practice and improve their skills in a new language. 

Core Functionality: 

The app is structured around five different types of language games, each targeting a specific skill: 

- Sentence Builder: Users are given a set of mixed-up words and must drag and drop them in the correct order to form a grammatically correct sentence. 
- Sentence Completion: A sentence is presented with a blank space. Users see a word with its letters scrambled (e.g., "koob" for "book") and must unscramble them to spell the correct word to complete the sentence. 
- Scrambled Word: Users see a word with its letters scrambled (e.g., "koob" for "book") and must unscramble them to spell the correct word, often with the help of a hint. 
- Match Sentence: The app plays an audio clip of a sentence. Users must listen carefully and select the correct written sentence from a list of similar-sounding options. 
- Listen Word: The app plays a sentence with a missing word (e.g., "I read a ____ every day."). Users must listen to the audio and then spell the missing word using a set of letter tiles. 

Key Technical Features: 

- Progress Tracking & Caching: The app intelligently saves the user's progress locally on the device using a CacheService. It records the sequenceNumber of the last successfully completed question. When the user reopens the app, it automatically continues from this point, fetching new questions from a remote server as needed.
- Clear Cache Feature: As per your request, a "Clear Cache" feature has been implemented. This allows the user to completely reset their progress for the current language and level. When activated, it clears the saved sequenceNumber, effectively setting it back to 1, and restarts the game from the very beginning.
- Modular Architecture: The project is well-organized with separate files for data models, API services (to communicate with the backend), and cache services (for local storage). This makes the code clean, maintainable, and scalable.
- Dynamic Content: The questions and answers are not hardcoded. The app fetches them dynamically from a server based on the selected language and proficiency level, allowing for a vast and ever-changing pool of content.
- User Experience (UX): The app features a clean, modern UI with neumorphic design elements. It includes features like text-to-speech (TTS) for pronunciation, loading indicators, error handling with retry options, and interstitial ads for monetization.
     

In summary, this is a comprehensive language learning toolkit that provides a variety of engaging exercises, remembers the user's place, and gives them full control to restart their learning journey at any time. 
Türkçe Açıklama 

Bu, dil öğrenme amacıyla Flutter ile geliştirilmiş bir mobil uygulamadır. Kullanıcıların yeni bir dildeki becerilerini pratik ederek geliştirmelerine yardımcı olmak için bir dizi interaktif, oyun benzeri alıştırma sunar. 

Temel İşlevsellik: 

Uygulama, her biri belirli bir beceriyi hedefleyen beş farklı türde dil oyunu etrafında yapılandırılmıştır: 

- Cümle Kurma (Sentence Builder): Kullanıcılara karışık bir kelime grubu verilir ve bunları sürükleyip bırakarak gramer açısından doğru bir cümle oluşturmalıdırlar. 
- Cümle Tamamlama (Sentence Completion): Boşluk bırakılmış bir cümle sunulur. Kullanıcılar, cümleyi tamamlamak için  harfleri karıştırılmış bir kelime görür (örneğin, "book" için "koob") ve ya bir ipucu yardımıyla yada ipucu olmaksızın harfleri doğru bir şekilde yazarak kelimeyi bulmalıdırlar. 
- Harfleri Karıştırılmış Kelime (Scrambled Word): Kullanıcılar harfleri karıştırılmış bir kelime görür (örneğin, "book" için "koob") ve genellikle bir ipucu yardımıyla harfleri doğru bir şekilde yazarak kelimeyi bulmalıdırlar. 
- Cümle Eşleştirme (Match Sentence): Uygulama bir cümlenin ses kaydını çalar. Kullanıcılar dikkatle dinlemeli ve benzer şekilde seslenen seçenekler arasından doğru yazılı cümleyi seçmelidir. 
- Dinle ve Yaz (Listen Word): Uygulama, eksik bir kelime içeren bir cümle çalar (örneğin, "Her gün bir ____ okurum."). Kullanıcılar sesi dinlemeli ve ardından bir harf grubunu kullanarak eksik kelimeyi yazmalıdır. 

Kilit Teknik Özellikler: 

- İlerleme Takibi ve Önbelleğe Alma (Caching): Uygulama, kullanıcının ilerlemesini CacheService kullanarak cihazda yerel olarak akıllıca kaydeder. Son başarıyla tamamlanan sorunun sequenceNumber (sıra numarasını) kaydeder. Kullanıcı uygulamayı yeniden açtığında, otomatik olarak bu noktadan devam eder ve gerektiğinde yeni soruları uzak sunucudan çeker.
- Önbelleği Temizle (Clear Cache) Özelliği: Talebiniz üzerine, "Önbelleği Temizle" özelliği uygulandı. Bu özellik, kullanıcının mevcut dil ve seviye için tüm ilerlemesini tamamen sıfırlamasına olanak tanır. Etkinleştirildiğinde, kaydedilmiş sequenceNumber'ı temizler, onu etkili bir şekilde 1'e geri ayarlar ve oyunu en baştan yeniden başlatır.
- Modüler Mimari: Proje, veri modelleri, API servisleri (arka uçla iletişim kurmak için) ve önbellek servisleri (yerel depolama için) için ayrı dosyalarla iyi bir şekilde organize edilmiştir. Bu, kodu temiz, bakımı kolay ve ölçeklenebilir hale getirir.
- Dinamik İçerik: Sorular ve cevaplar kodun içine gömülü değildir. Uygulama, seçilen dile ve yeterlilik seviyesine göre bunları dinamik olarak bir sunucudan çeker, bu da geniş ve sürekli değişen bir içerik havuzu sağlar.
- Kullanıcı Deneyimi (UX): Uygulama, neomorfik tasarım öğeleriyle temiz, modern bir kullanıcı arayüzüne sahiptir. Telaffuz için metin-okuma (TTS), yüklenme göstergeleri, yeniden deneme seçenekleriyle hata yönetimi ve para kazanma için ara reklamlar gibi özellikler içerir.
     

Özetle, bu, çeşitli ilgi çekici alıştırmalar sunan, kullanıcının nerede kaldığını hatırlayan ve öğrenme yolculuğunu istediği zaman yeniden başlaması üzerinde tam kontrol veren kapsamlı bir dil öğrenme araç setidir. 
