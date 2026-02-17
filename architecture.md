# Arsitektur Sistem

## Gambaran Umum
Aplikasi Sistem Peminjaman Ruangan Kampus menggunakan arsitektur
client-server dengan pemisahan frontend dan backend.

## Alur Sistem
1. Frontend mengirim request ke Backend melalui REST API
2. Backend memproses request dan berinteraksi dengan database
3. Backend mengirim response ke Frontend

## Arsitektur Logis

[Frontend]
    |
    | HTTP / REST API
    v
[Backend - ASP.NET Core Web API]
    |
    v
[Database - SQL Server]

## Pertimbangan Arsitektur
- Pemisahan frontend dan backend untuk kemudahan pengembangan
- Backend bersifat stateless
- Database menggunakan pendekatan soft delete
