# DuoVerse

Project Android untuk platform game duo.

## Build dari GitHub Actions
Workflow build sudah dapat dipasang di `.github/workflows/build.yml`.

## Supabase
Client menggunakan Project URL dan anon key yang diberikan pemilik project.
Jangan pernah memasukkan `service_role` atau secret key ke aplikasi.

## Catatan
Build ini adalah fondasi client + room multiplayer. Gameplay 15 game belum merupakan 15 game penuh.
Backend Supabase harus memiliki tabel/RPC yang sesuai (`profiles`, `rooms`, `room_players`, `create_room`, `join_room`) dan RLS yang benar.

Copyright © Rey & Luthfie 2026–2027 · DuoVerse
