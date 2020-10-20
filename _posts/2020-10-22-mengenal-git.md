---
layout: post
title: git dan versioning control system
image: 
bigimg: 
    - ""
tags: [github, gitlab, version control system,]
comments: true
---

bismillah 
seperti judul postingan saya ingin mengenalkan salah satu teknologi control version system,
jadi version control system adalah sebuah sistem yang merekan perubahan perubahan dari sebuah file atau folder dari timeline yang ditentukan hingga dapat melakukan rollback terhadap perubahan yang tidak ingin dilakukan. seperti programmer ingin membuat fitur tetapi pada fitur tersebut terjadi kesalahan pada saat production, jadi mau tidak mau sang programmer melakukan rollback dan balik ke fitur yang sebelumnya.

## Tujuan git
- speed
- simple design
- strong support dari berbagai macam orang
- terdistribusi penuh 

## git tidak terhapus
- secara konsep git tidaklah menghapus tetapi melakukan penambahan
- pada saat melakukan kesalahan bisa melakukan recovery atau pemulihan
- pemulihan agak sedikit tricky wkwkw


## configurasi dasar
```javascript
$ git config --global user.name "yogiex"
$ git config --global user.email "yogiex@contoh.com"
```
## membuat inisiasi repository

```javascript
$ mkdir new-repo
$ cd new-repo
$ git init
```

## mengcopy repository dari github ke komputer local kita

```javascript
$ git clone https://github.com/yogiex/example
$ cd example/
```
## command dasar pada git
git add digunakan pada saat setelah melakukan perubahan pada suatu file atau folder digunakan untuk menambahkan file atau content pada index status
```javascript
$ git add file.py
```

git status merupakan command untuk melakukan pengecekan pekerjaan tree status
```javascript
$ git status
```