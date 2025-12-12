# 📂 Karma Projeler ve Araçlar Kütüphanesi / Mixed Projects Library

**Dil Seçimi / Language Selection**
[ 🇹🇷 Türkçe İçerik ](#-türkçe-içerik) | [ 🇬🇧 English Content ](#-english-content)

---

# 🇹🇷 Türkçe İçerik

Bu depo (repository), yazılım geliştirme sürecimde üzerinde çalıştığım farklı disiplinlere ait projeleri, araçları ve deneyimleri içermektedir. Veri biliminden siber güvenliğe, retro programlamadan modern yapay zeka promptlarına kadar çeşitli çalışmalar burada toplanmıştır.

## 🚀 Proje İçerikleri ve Kategoriler

### 1. 🧠 Yapay Zeka ve Derin Öğrenme (Machine Learning)
**Dosya:** `mumpy_CNN.ipynb`

Ses verilerini sınıflandırmak için geliştirilmiş bir **Derin Öğrenme (CNN - Convolutional Neural Network)** projesidir.
* **Veri Seti:** "Urban Sounds" veri seti kullanılarak şehir sesleri analiz edilir.
* **Teknolojiler:** Python, TensorFlow/Keras, Pandas, Matplotlib, Librosa.
* **İşlev:** Ses dosyalarının spektrogramlarını analiz eder, model eğitimi yapar ve doğruluk (accuracy) grafiklerini oluşturur.

### 2. 🔐 Siber Güvenlik ve Otomasyon
**Dosya:** `ZIPPassAlalyzer.sh`

Kali Linux veya benzeri dağıtımlarda şifreli ZIP dosyalarının parolasını kırmak için kullanılan **John the Ripper** aracını otomatize eden bir Bash scriptidir.
* **Nasıl Çalışır:** Kullanıcıdan hedef dosya yolunu alır, `zip2john` aracı ile dosyanın hash'ini çıkarır ve ardından `john` aracı ile bu hash'i kırmaya çalışır.
* **Kullanım:** Terminal üzerinden çalıştırılır (Örn: `./ZIPPassAlalyzer.sh`).

### 3. 🤖 ChatGPT ve Prompt Mühendisliği
**Dosya:** `ChatGPT Dev Mode.md`

Büyük Dil Modellerinin (LLM) sınırlarını test etmek, güvenlik filtrelerini aşmak ve "Geliştirici Modu" (Developer Mode) veya "DAN" (Do Anything Now) gibi kişilikleri aktif etmek için derlenmiş prompt koleksiyonudur.
* **İçerik:** DAN, STAN, DUDE ve Mongo Tom gibi çeşitli jailbreak senaryolarını içerir.

### 4. 💾 Retro Programlama ve Algoritmalar (QuickBasic)
**Kaynak Kod:** `QuickBasic_NotHesaplama` | **Uygulamalar:** `.exe` dosyaları

Temel programlama mantığını kavramak için QuickBasic kullanılarak geliştirilmiş klasik konsol uygulamalarıdır.
* **Not Hesaplama:** Vize ve Final notlarına göre harf notu hesaplar. Kullanıcı hesaplama oranlarını (Örn: %40 Vize, %60 Final) değiştirebilir.
* **Diğer Araçlar:** `Tahmin Oyunu.exe` (Sayı tahmin algoritması), `Burcunu Hesapla.exe` (Tarih tabanlı burç bulma), `AdveSoyadAyriYazdir.exe` (String işleme).

### 5. 📐 Teknik Dokümantasyon ve Görseller
* **8085.png:** Intel 8085 mikroişlemcisi, RAM, ROM ve I/O üniteleri arasındaki veri ve adres yollarını gösteren teknik devre şeması.
* **scrum.png:** Yazılım geliştirme süreçlerinde kullanılan Çevik (Agile) SCRUM metodolojisinin akış diyagramı.

## ⚠️ Yasal Uyarı
Bu repoda yer alan siber güvenlik araçları (özellikle `ZIPPassAlalyzer`) ve prompt koleksiyonları **tamamen eğitim ve araştırma amaçlıdır**. Bu araçların izinsiz kullanımı kullanıcının sorumluluğundadır.

---
---

# 🇬🇧 English Content

This repository contains a diverse collection of projects, tools, and experiments developed across different disciplines of software engineering. The collection spans from Data Science and Cybersecurity to Retro Programming and Modern AI Prompt Engineering.

## 🚀 Projects and Categories

### 1. 🧠 Artificial Intelligence & Deep Learning
**File:** `mumpy_CNN.ipynb`

A **Deep Learning (CNN - Convolutional Neural Network)** project designed to classify audio data.
* **Dataset:** Analyzes urban sounds using the "Urban Sounds" dataset.
* **Technologies:** Python, TensorFlow/Keras, Pandas, Matplotlib, Librosa.
* **Functionality:** Performs spectrogram analysis on audio files, trains a model, and visualizes accuracy and loss metrics.

### 2. 🔐 Cybersecurity & Automation
**File:** `ZIPPassAlalyzer.sh`

A Bash script designed to automate the usage of **John the Ripper** for cracking encrypted ZIP passwords on Kali Linux or similar distributions.
* **Workflow:** Takes the target file path from the user, extracts the file hash using `zip2john`, and attempts to crack the hash using `john`.
* **Usage:** Executed via the terminal (e.g., `./ZIPPassAlalyzer.sh`).

### 3. 🤖 ChatGPT & Prompt Engineering
**File:** `ChatGPT Dev Mode.md`

A collection of prompts curated to test the limits of Large Language Models (LLMs), bypass safety filters, and activate personas like "Developer Mode" or "DAN" (Do Anything Now).
* **Content:** Includes various jailbreak scenarios such as DAN, STAN, DUDE, and Mongo Tom.

### 4. 💾 Retro Programming & Algorithms (QuickBasic)
**Source Code:** `QuickBasic_NotHesaplama` | **Applications:** `.exe` files

Classic console applications developed using QuickBasic to demonstrate fundamental programming logic.
* **Grade Calculator:** Calculates letter grades based on Midterm and Final scores with customizable ratios.
* **Other Tools:** `Tahmin Oyunu.exe` (Number guessing algorithm), `Burcunu Hesapla.exe` (Zodiac sign calculator), `AdveSoyadAyriYazdir.exe` (String manipulation).

### 5. 📐 Technical Documentation & Visuals
* **8085.png:** A technical circuit schematic illustrating data and address buses between the Intel 8085 microprocessor, RAM, ROM, and I/O units.
* **scrum.png:** A flowchart diagram explaining the Agile SCRUM methodology used in software development processes.

## ⚠️ Legal Disclaimer
The cybersecurity tools (specifically `ZIPPassAlalyzer`) and prompt collections provided in this repository are intended **solely for educational and research purposes**. The user is fully responsible for any unauthorized use.

---

## 📬 Contact / İletişim

Feel free to reach out for suggestions, error reports, or improvements regarding the code.
Kodlarda geliştirilebilecek yerler, hatalar veya önerileriniz için iletişime geçmekten çekinmeyin.

**Developer:** Yuasset
