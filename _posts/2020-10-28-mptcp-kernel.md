---
layout: post
title: mptcp kernel
image: 
bigimg: 
    - ""
tags: [linux, kernel, operating system]
comments: true
---

sobat github, mari berkenalan dengan varian kernel linux yang tidak biasa digunakan untuk keseharian, mungkin ada beberapa yang tidak familiar dengan kernel, 

# defini sedikit tentang kernel

jadi kernel itu adalah komponen utama dari suatu sistem operasi(SO) dan inti dari penghubung antara perangkat keras komputer dan proses. keduanya berkomunikasi dengan memanejemen sumber daya se efisien mungkin

# kernel itu ngapain aja sih?
 - memory management
 - process management
 - device drivers
 - system call and security

 # dimana kernel itu yang cocok dengan OS?
 - hardware atau perangkat keras
 - linux kernel
 - user processes


 # MPTCP kernel 
 multipath Transmission Control Protocols(MP-TCP) adalah jenis kernel yang memungkinkan pengguna menggunakan beberapa interfaces atau Internet Protocol(IP) dengan memodifikasi Transmission Control Protocols(TCP) dengan mengirimkan packet transfer ke beberapa interface yang terhubung, istilah untuk MPTCP ialah sub-flow pada tiap interfaces yang terhubung. 

 # kenapa harus menggunakan MPTCP kernel
keuntungan menggunakan MPTCP kernel adalah pemanfaatan daya yang lebih baik dibandingkan single path TCP(SPTCP) atau TCP yang biasa, dengan trhougput yang lebih baik juga, lebih halus tanpa mengganggu interfaces pada saat pengiriman data