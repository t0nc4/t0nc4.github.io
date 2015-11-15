---
layout: post
title: Hello jekyll, Thanks github
---


Yap.. ini blog yang kesekitan kalinya, dari dulu keinginan untuk bisa menuangkan sesuatu ke dalam tulisan melalui media blog karena paling mudah untuk mempublish sebuah tulisan. Tapi ternyata hal termudah belum tentuh mudah di lakukan buat aku. Biasanya saat ingin mempublish sebuah tulisan dalam media blog pada umumnya kita perlu untuk login ke web adminnya lalu posting disitu, saya sudah mencoba menuliskan dulu tulisan dalam bentuk draft di text file lalu login & mempostingkannya, juga pernah coba posting lewat email tetapi tetap saja untuk formating tulisan secara mendetail perlu login ke web adminnya untuk mengedit secara langsung step itu kadang membuat malas untuk posting, belum lagi kalau untuk memodifikasi websitenya diperluka step-step extra dengan edit & uploadnya.

Kali ini saya mencoba cara lain yang siapa tau bisa membuat rasa berbeda dalam memposting tulisan. Saya mencoba free page dari github & menggunakan jekyll, alasan utamanya karena dengan jekyll + github selain gratis saya hanya perlu mencatat pada text file & kemudian push ke github untuk publikasinya, semua di lakukan tanpa perlu login ke web admin atau send via email dan modifikasi web bisa di lakukan secara mudah sehingga serasa hostingnya di komputer sendiri.

Kalau ingin juga mencoba untuk blogging di pagenya github bisa mengikuti cara saya berikut. Hal yang pertama perlu di persiapkan adalah

* [github](https://github.com/) account, kemudian buat repo dengan nama username_github_anda.github.io
* git apps.
* text edtor.

Untuk mempermudah hidup saya menggunakan template yang udah jadi untuk jekyll, disini saya menggunakan [poole](http://getpoole.com/) dengan template [hyde](https://github.com/poole/hyde), berikut perintah yang saya gunakan, jangan lupa ganti semua text <em>username_github_anda</em> sesuai dengan username github anda:

{% highlight bash %}
git clone https://github.com/poole/hyde.git
cd hyde 
git remote set-url origin https://github.com/username_github_anda/username_github_anda.github.io.git
git push origin master
{% endhighlight %}

Setelah melakukan perintah diatas sebenarnya blog anda sudah online dengan alamat http://username_github_anda.github.io tetapi dengan seting default jadi sekarang tinggal menyesuaikan blog yang ada seperti yang anda mau & kemudian push kembali ke github.

> ###Referensi
> [jekyll docs](http://jekyllrb.com/docs) <br />
> [markdown syntax](https://daringfireball.net/projects/markdown/syntax) <br />
> [hyde options](https://github.com/poole/hyde#options) <br />

