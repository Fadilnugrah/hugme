---
title: "Configurasi untuk neovim + autocomplete python?"
date: 2021-10-22T02:21:02Z
tags: ['neovim','code-editor','linux']
draft: false
---

# configurasi neovim

Hallo kawan kawan, sekarang saya ingin membahas gimana cara memasang configurasi
neovim theme + autocomplete python, neovim adalah sebuah code editor yang
basednya dari vim khusus command line dan gak kalah ama yg sebelah seperti
VSCode, py-charm, sublime text, ternyata neovim/vim juga gak kalah keren
loh.</br>

Sekarang kita bahas apa saja yg perlu di install?, ya tentu saja install
terlebih dahulu neovim nya </br>
> __$home:__ apt-get install neovim -y</br>
> __$home:__ apt-get install nodejs-lts</br>
> __$home:__ apt-get install git -y</br>
>
Jika sudah install package di atas mari kita eksekusi plug nya..</br>
> __$home:__ git clone https://github.com/Gitcomeon8/dotfiles</br>
> __$home__ mv dotfiles/nvim .config/</br>
>
Nah itu sudah di pindahkan yaa plug serta configurasinya kedalam file .config, 
Setelah itu masuk ke neovim.</br>

> __$home:__ nvim</br>

Nanti akan masuk ke tampilan neovim nya, kalian cukup ketik perintah di bawah ini</br>

> :PlugInstall </br>
Kalau sudah selanjutnya install autocompletenya </br>
> :CocInstall coc-pyright </br>

Tunggu hingga selesai :)

**NOTE!** Jika terjadi Error pada coc nya install di bawah ini </br>
> __$home:__ npm i https://github.com/Qix-/node-error-ex</br>
> __$home:__ npm install </br>

Terimakasih ....
