# 🚀 GitHub Organization Management  

## 1. Quản lý theo **Topic**  
- **a. Quy tắc đặt tag topic**  
  - Gán nhiều tag nếu phù hợp, nhưng **3 tag đầu tiên phải unique**.  
  - **`prod`** – 🔥 Repositories tự phát triển.  
  - **`outsource`** – 🤝 Repositories làm outsource.  
  - **`chore`** – 🛠️ Mini feature, demo, sponsor.  
  - **`libs`** – 📦 Libraries và frameworks.  
  - **`merchant-{name}`** – 🏢 Dùng để filter các repo của **một project**.  

- **b. Quy tắc đặt tên repository**  
  - Format:  
    ```  
    {branch} - {project_name} - {platform}  
    ```  
  - Ví dụ:  
    ```
    vnlook-iorder-web
    ```

---

## 2. Quản lý **Permissions**  
- **Project tự phát triển**  
  - 🔒 **Private**  
  - 🏷 **Topics**: `prod`, `vnlook`  

- **Project outsource**  
  - 🔒 **Private**  
  - 🏷 **Topics**: `outsource`, `<name>`  

- **Project demo tính năng hay ho**  
  - 🌍 **Public**  
  - 🏷 **Topics**: `chore`, `vnlook`  

- **Project fork từ team khác**  
  - 🌍 **Public**  
  - 🏷 **Topics**: `prod`, `vnlook`  

- **Frameworks & Libraries**  
  - 🌍 **Public**  
  - 🏷 **Topics**: `prod`, `vnlook`, `libs`  

---

📌 **Tuân theo các quy tắc không được sai sót.** 🚀🔥  
