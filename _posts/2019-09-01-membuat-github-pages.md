---
layout: post
title:  "Membuat Github Pages menggunakan Jekyll secara lokal"
date:   2019-09-01 23:00:00 +0700
tag: "github"
categories: learn
update:	
author: bagoes
---
Tulisan ini hanya sebagai contoh membuat blog di Github Pages menggunakan Jekyll. Bagaimana cara membuatnya dari [sini][link-github]{:target="_blank"}.

Ini beberapa poin catatan bagaimana cara menjalankan website ini secara lokal:
1. Download & install GitHubDesktop sebagai aplikasi antar muka pada komputer.
2. Clone repository dari blog saya di server github ke folder di komputer saya.
3. Download & install Git, pilih yang 1 & RubyInstaller buat install Jekyll.
4. Download & install Notepad++ buat text editor.
5. Edit file ini pada folder _post dari repository yang telah clone ke komputer pake notepad++. Save & jangan lupa backup dulu sebelum dirubah.
6. Klik kanan pada folder clone & buka GitBash 
	`rekomendasi dari github menggunakan bundler`
	$ bundle install
	$ git add Gemfile Gemfile.lock
	`jalankan Jekyll secara lokal`
	$ bundle exec jekyll serve
7. Buka browser buat liat preview dibuka secara lokal http://localhost:4000

[link-github]: https://help.github.com/en/github/working-with-github-pages/getting-started-with-github-pages