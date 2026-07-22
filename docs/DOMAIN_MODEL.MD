# TaskFlow Domain Model

## User

Deskripsi : Mewakili user yang dapat login ke dalam sistem

Memiliki:
- Projects
- Notifications
- Profile

---

## Project

Deskripsi : Workspace tempat seluruh tugas dilakukan

Memiliki:
- Members
- Boards
- Activities
- Labels

---

## Board

Deskripsi : Kolom Kanban seperti to do, doing, done

Memiliki:
- Tasks

---

## Task

Deskripsi : tugas yang harus diselesaikan

Memiliki:
- Checklist
- Comments
- Attachments
- Labels
- Activity

---

## Checklist

Deskripsi : Bagian kecil dari Task

---

## Comment

Deskripsi : Diskusi pada Task

---

## Attachment

Deskripsi : File yang diunggah pada Task

---

## Notification

Deskripsi : Pemberitahuan kepada User

---

## Activity

Deskripsi : Riwayat aktivitas sistem