<h1 align="center"> NLP With HuggingFace Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> Analisis </h2> 

- Zero-Shot Classification

Merupakan jenis klasifikasi dengan metode Zero-Shot yang menurut saya sangat menarik untuk dicoba karena memungkinkan klasifikasi teks ke dalam label tertentu tanpa pelatihan tambahan. Dalam proyek deteksi hama pada tanaman cabai dan deteksi objek berbahaya yang saya gunakan, metode ini memberikan skor kepercayaan untuk menilai kesesuaian deskripsi proyek dengan label yang telah ditetapkan, sehingga memudahkan pengelompokan proyek meskipun data latih khusus tidak tersedia.

- Text Generation

Pipeline text-generation menggunakan model seperti distilgpt2 untuk menghasilkan teks lanjutan berdasarkan prompt awal. Menurut saya, pipeline ini sangat berguna dalam mengembangkan deskripsi proyek, karena bisa membantu menghasilkan kalimat atau paragraf yang kaya dengan konteks. Fungsinya sangat fleksibel, memungkinkan pengembangan ide deskripsi atau menghasilkan teks yang sesuai dengan gaya dan tema proyek tertentu.

- Fill-Mask

Pipeline fill-mask bertujuan memprediksi kata yang hilang dalam kalimat. Saya menemukan pipeline ini sangat membantu untuk menyempurnakan deskripsi proyek yang belum lengkap atau ketika ada kebutuhan untuk menemukan kata yang relevan dan kontekstual. Dengan cara ini, deskripsi proyek bisa dilengkapi dengan kosakata yang lebih sesuai, membantu memperkaya teks secara otomatis.

- Named Entity Recognition (NER)

NER adalah pipeline yang mengelompokkan kata atau frasa ke dalam kategori tertentu seperti lokasi, organisasi, atau individu. Dalam proyek, pipeline ini sangat bermanfaat untuk identifikasi entitas penting dalam deskripsi, seperti nama tempat atau subjek utama proyek. Dengan demikian, pipeline NER membantu mengenali elemen spesifik yang relevan dalam deskripsi proyek.

- Question Answering (QA)

Pipeline QA menggunakan model seperti distilbert-base-cased-distilled-squad untuk menjawab pertanyaan berdasarkan konteks yang diberikan. Ini sangat menarik, terutama ketika diperlukan jawaban atas pertanyaan terkait deskripsi proyek yang sudah ada. Pipeline ini dapat mengakses informasi spesifik dalam teks, memudahkan pencarian detail dari konten proyek.

- Sentiment Analysis

Pipeline sentiment analysis berfungsi untuk mengidentifikasi sentimen atau emosi dalam teks. Dalam konteks proyek, pipeline ini bermanfaat untuk menganalisis kesan umum dari deskripsi atau memahami aspek emosional yang mungkin terkait dengan proyek. Dengan informasi ini, kita dapat mengetahui persepsi umum yang tercermin dalam deskripsi proyek tersebut.

- Summarization

Pipeline summarization dirancang untuk merangkum teks panjang menjadi versi yang lebih singkat tanpa kehilangan poin-poin utama. Dalam proyek, pipeline ini sangat membantu ketika deskripsi proyek terlalu panjang, memudahkan penyajian informasi utama secara lebih ringkas dan padat.

- Translation

Pipeline translation, yang menggunakan model seperti Helsinki-NLP/opus-mt-id-en, memungkinkan penerjemahan teks dari Bahasa Indonesia ke Bahasa Inggris. Saya merasa pipeline ini sangat berguna untuk memperluas jangkauan deskripsi proyek kepada audiens internasional, memudahkan mereka untuk memahami konten proyek yang ditulis dalam bahasa Indonesia.
