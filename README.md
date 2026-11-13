# VTX Lapis — Public Preview

VTX Lapis is a desktop database manager for PostgreSQL, MySQL / MariaDB, SQL Server, SQLite, MongoDB and Redis:
browse and edit tables, write and run queries, manage users and roles. Everything stays on your computer: no
account, no cloud. Saved passwords go to your system's
keychain (macOS Keychain, Windows Credential Manager).

**This repository holds the release files only.** Get VTX Lapis from
[**Releases → the latest one**](https://github.com/tanawat011/vtx-lapis-release/releases/latest):

| Your computer | The file to download |
| --- | --- |
| Mac (Apple silicon or Intel) | `VTX-Lapis_<version>_universal.dmg` |
| Windows 10 / 11 | `VTX-Lapis_<version>_x64_portable.zip` — unzip and run `VTX Lapis.exe`, nothing to install |

`SHA256SUMS.txt` beside them lists each file's checksum.

## Public Preview — the Free edition

What you download here is the **Free edition**, free to use: every engine, as many connections as you like,
browsing, queries and editing, CSV export, SSH tunnels, query files, and Users & Roles.

These are **Pro** — they stay in the app, marked PRO, and are not out yet: Back up, Restore, Clone,
Copy table, export as JSON or SQL, Compare schemas & data, the ER diagram, Performance and Sessions.

It is a preview: **back up a database before you use VTX Lapis on data you care about**, and try it on a copy
first where you can.

## Upgrading from Vatol or an older build

The app was called Vatol. From 0.3.0 the first launch copies what the old name kept — connections, query files,
open tabs, preferences — and never changes or deletes it; each saved password comes over the first time its
connection opens. Quit the old app first. On Windows, copy the old `data` folder next to the new `VTX Lapis.exe`
before the first launch. The release notes have the steps.

## The first time you open it

VTX Lapis is not signed yet, so your computer asks once.

- **macOS 15 and later:** open it, click Done, then System Settings → Privacy & Security → Open Anyway (next to "VTX Lapis").
- **macOS 14 and earlier:** right-click VTX Lapis in Applications → Open → Open.
- **Windows:** if "Windows protected your PC" shows, click More info → Run anyway. Before unzipping: right-click the zip → Properties → tick Unblock → OK.

## New to it?

New Connection → Demo Shop opens a small shop database (SQLite, made on your computer) with tables, views,
a trigger and foreign keys to try things on.

## Updates

VTX Lapis asks GitHub once a day for the latest release here and tells you when a newer one is out. It never
downloads or installs anything by itself.

## Found a problem?

Open an issue here: [Issues → New issue](https://github.com/tanawat011/vtx-lapis-release/issues/new). Say what you did, what you expected and what happened, with the version (VTX Lapis → About) and
your operating system. View → Activity Log shows what the app did last. Never paste a password or a
connection string with one in it.

---

**ภาษาไทย:** VTX Lapis เป็นโปรแกรมจัดการฐานข้อมูล (PostgreSQL, MySQL / MariaDB, SQL Server, SQLite, MongoDB, Redis)
ข้อมูลอยู่ในเครื่องทั้งหมด ไม่มีบัญชี ไม่มี cloud · **ที่นี่คือรุ่น Free ใช้ฟรี** ส่วน Back up, Restore, Clone, Copy table, export JSON / SQL,
Compare, ER diagram, Performance, Sessions เป็น Pro (ยังไม่เปิดขาย) ·
ดาวน์โหลดจาก [Releases](https://github.com/tanawat011/vtx-lapis-release/releases/latest) — Mac เอา `universal.dmg`,
Windows เอา `x64_portable.zip` · ยังไม่ได้ sign: ครั้งแรกต้องกดอนุญาต (ดูข้างบน) · ยังเป็น preview: สำรองฐานข้อมูลก่อนใช้กับข้อมูลสำคัญ ·
เจอปัญหา: เปิด [Issue](https://github.com/tanawat011/vtx-lapis-release/issues/new)
