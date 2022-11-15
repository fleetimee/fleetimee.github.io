---
layout: post
title: Otomatisasi workflow Flutter dengan CI/CD menggunakan Github Actions 🚀 (dari Github ke PlayConsole)
slug: flutter-ci-cd
---

## Intro

CI/CD digunakan untuk mempermudah developer dalam melakukan proses build, test, dan deploy aplikasi. Dengan CI/CD, developer tidak perlu melakukan build, test, dan deploy secara manual. CI/CD akan melakukan build, test, dan deploy secara otomatis. Dengan CI/CD, developer dapat fokus pada proses development aplikasi, sehingga developer dapat menghemat waktu dan meningkatkan produktivitas.

Dalam guide ini akan dibahas bagaimana cara melakukan CI/CD pada aplikasi Flutter menggunakan Github Actions. 

> Untuk unit test tidak dibahas ya disini hanya fokus ke build dan deploy saja 🤣

## Persiapan
- Punya akun Github dan mengerti dasar-dasarnya (Push, Pull, Fork, PR, dll)
- Project Flutter yang sudah jalan di lokal
- (Opsional) Akun Play Console untuk melakukan deploy secara otomatis ke Play Store