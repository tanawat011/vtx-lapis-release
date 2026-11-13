# VTX Lapis — Public Preview

VTX Lapis is a desktop database manager for PostgreSQL, MySQL / MariaDB, SQL Server, SQLite, MongoDB and Redis:
browse and edit tables, write and run queries, compare schemas and data, back up and restore, see what the
server is doing. Everything stays on your computer: no account, no cloud. Saved passwords go to your system's
keychain (macOS Keychain, Windows Credential Manager).

**This repository holds the release files only.** Get VTX Lapis from
[**Releases → the latest one**](https://github.com/tanawat011/lapis-releases/releases/latest):

| Your computer | The file to download |
| --- | --- |
| Mac (Apple silicon or Intel) | `VTX-Lapis_<version>_universal.dmg` |
| Windows 10 / 11 | `VTX-Lapis_<version>_x64_portable.zip` — unzip and run, nothing to install |

`SHA256SUMS.txt` beside them lists each file's checksum.

## Public Preview

VTX Lapis is free during the Public Preview. Some features may become part of a paid Pro version later.

It is a preview: **back up a database before you use VTX Lapis on data you care about**, and try it on a copy
first where you can.

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

Open an issue here: [Issues → New issue](https://github.com/tanawat011/lapis-releases/issues/new). Say what you did, what you expected and what happened, with the version (VTX Lapis → About) and
your operating system. View → Activity Log shows what the app did last. Never paste a password or a
connection string with one in it.

---

**ภาษาไทย:** VTX Lapis เป็นโปรแกรมจัดการฐานข้อมูล (PostgreSQL, MySQL / MariaDB, SQL Server, SQLite, MongoDB, Redis)
ข้อมูลอยู่ในเครื่องทั้งหมด ไม่มีบัญชี ไม่มี cloud · **Public Preview: ใช้ฟรีช่วงนี้** บางฟีเจอร์อาจเป็น Pro ภายหลัง ·
ดาวน์โหลดจาก [Releases](https://github.com/tanawat011/lapis-releases/releases/latest) — Mac เอา `universal.dmg`,
Windows เอา `x64_portable.zip` · ยังไม่ได้ sign: ครั้งแรกต้องกดอนุญาต (ดูข้างบน) · ยังเป็น preview: สำรองฐานข้อมูลก่อนใช้กับข้อมูลสำคัญ ·
เจอปัญหา: เปิด [Issue](https://github.com/tanawat011/lapis-releases/issues/new)
