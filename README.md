# TANGA SUPER APP — PUBLIC ANDROID RELEASES

This repository is the **public download channel** for the TANGA SUPER APP Android
build. It contains release information and the APK artefact only — the application
source is maintained in a private repository.

## Download

Open the [Releases](../../releases) page and download **TANGA_SUPER_APP.apk** from the
latest release.

| Item | Value |
| --- | --- |
| Application | TANGA SUPER APP |
| Package (application id) | `com.tanga.superapp` |
| Version / build | `1.1.0` (versionCode `2`) |
| Minimum Android | 6.0 (API 24) |
| Target Android | API 36 |
| Backend | `https://tanga-super-backend.onrender.com` |
| Super Admin dashboard | `https://tanga-control-center.onrender.com` |

## One app, three experiences

The single APK contains the **Customer**, **Vendor** and **Rider** experiences. The
experience you see is decided by the backend after you sign in:

| Backend state | What the app shows |
| --- | --- |
| `role = customer` | Customer dashboard (food, orders, profile) |
| pending vendor / rider application | Application status screen (pending / information requested / rejected) |
| approved vendor (`role = vendor`) | Vendor dashboard |
| approved rider (`role = rider`) | Rider dashboard |

Nobody can grant themselves a vendor or rider role from the app: an application is
always created as **PENDING** and the Founder approves it in the TANGA Control Center.

## Install

1. Download `TANGA_SUPER_APP.apk` on an Android phone.
2. Allow "Install unknown apps" for the browser/file manager you downloaded with.
3. Open the APK and install it.
4. Register with a phone number and password, sign in, then optionally apply as a
   vendor or rider from **Profile → Vendor & Rider Applications**.

The APK is signed with the TANGA release key. SHA-256 of the signing certificate:
`56:60:5B:F1:78:F6:A6:9C:35:EB:71:16:57:FD:62:E7:C0:72:A9:D8:01:04:59:26:A7:50:D5:E1:80:06:E1:4C`.

## Availability

Tanzania is the initial operating market. Food delivery depends on participating
vendors and riders in the area — the app never claims coverage that does not exist.
