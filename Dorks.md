## 🔑 Admin Panel Dorks

site:domain.com inurl:/admin
site:domain.com inurl:/admin/login
site:domain.com inurl:/admin.aspx
site:domain.com intitle:"admin login"
site:domain.com intitle:"index of" inurl:admin

---

## 📂 Information Disclosure

site:domain.com ext:log
site:domain.com ext:env
site:domain.com ext:conf
site:domain.com ext:bak
site:domain.com ext:backup
site:domain.com ext:old
site:domain.com ext:git
site:domain.com ext:svn
site:domain.com ext:htaccess
site:domain.com ext:htpasswd

---

## ☁ Cloud Storage Exposure

site:s3.amazonaws.com "domain.com"
site:firebaseio.com "domain.com"
site:blob.core.windows.net "domain.com"
site:googleapis.com "domain.com"
site:drive.google.com "domain.com"


---

## 💉 SQL Injection Dorks

site:domain.com inurl:"id="
site:domain.com inurl:"page="
site:domain.com inurl:"details.php?id="
site:domain.com inurl:"index.php?page="


---

## 🗄 Backup & Sensitive Files

site:domain.com filetype:sql
site:domain.com filetype:zip
site:domain.com filetype:tar
site:domain.com filetype:gz
site:domain.com filetype:rar
site:domain.com filetype:7z
site:domain.com filetype:db


---

## 🔑 API Key Disclosure

site:pastebin.com intext:"APIKey" "domain.com" -github
site:pastebin.com intext:"APISecret" "domain.com" -github
site:pastebin.com intext:"API-Token" "domain.com" -github


---

## 📅 Date-Based Searches

site:domain.com after:2023-01-01 before:2023-12-31

---

## 🧪 Logs & Debug Files

site:domain.com ext:log
site:domain.com ext:txt intext:"error"
site:domain.com intext:"stack trace"
site:domain.com intext:"debug"

## ◾ Git / Dev Artifacts

site:domain.com ".git"
site:domain.com ".svn"
site:domain.com ".DS_Store"


