# 📌 Enhanced Download Button  
[![Built with HTML](https://img.shields.io/badge/Built%20with-HTML-orange)](#)
[![Built with CSS](https://img.shields.io/badge/Built%20with-CSS-blue)](#)
[![Built with JavaScript](https://img.shields.io/badge/Built%20with-JavaScript-yellow)](#)
[![License](https://img.shields.io/badge/License-GPL_3.0-blue.svg)](LICENSE)
[![Vercel](https://img.shields.io/badge/Hosted%20on-Vercel-black?logo=vercel)](https://download-button-three.vercel.app/)
[![Developer](https://img.shields.io/badge/Developer-Asif%20Kamboh-blue?style=flat)](https://www.asifkamboh.com)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=AsifKamboh-COM.download-button)](#)


![Enhanced Download Button](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhgX2NBmPPEOfYdnvpK1162qW1K9v6Ca5Zjk_peDbbkrp-jGWPjTsekps-fV7L2AeI1n2PyYXN67MhI6rJ9nm2HGwsYpqRTIrFOOZ_YUicyakHbS63_JASdoUFhHMCtctJ9_SnEhbaQwl2UrnPp7Nn5uYV-I56PzB8ka2qA5JYLiJ-OtlOjyDlcQXvGXFfE/s1600/download_button.png)

🔗 **Live Demo:** [Enhanced Download Button](https://download-button-three.vercel.app/)  

---

## ⭐ About  
The **Enhanced Download Button** is a stylish, modern, and animated button designed for seamless file downloads. It features:  

✅ **Beautiful gradient animations** for an eye-catching UI.  
✅ **Download counter** that updates dynamically using an external API.  
✅ **Loading spinner** and error handling for a smooth user experience.  
✅ **Fully responsive design**, working across mobile & desktop devices.  
✅ **Deployed on Vercel** for fast and reliable performance.  

---

## 📂 Folder Structure  

```
📂 download-button/         # Root directory
 ┣ 📂 public/               # Public folder for static files
 ┃  ┗ 📄 index.html         # Main HTML file with the download button
 ┣ 📄 LICENSE               # License file (GPL-3.0)
 ┣ 📄 README.md             # Documentation with setup & usage details
 ┣ 📄 vercel.json           # Vercel configuration file
 ┗ 📄 package.json          # Project metadata & scripts
```

---

## 🌟 Features & Functionalities  

### 🎨 **Modern UI & Animations**  
- Gradient **hover effects** for a smooth look.  
- **Loading animation** when the file is downloading.  
- Elegant **shadow and hover transformations**.  

### 🔢 **Real-time Download Counter**  
- Fetches **current download count** from an API.  
- **Increments download count** upon each file download.  
- Displays the counter in a **styled badge**.  

### 🛑 **Error Handling & Smooth User Experience**  
- If the download fails, the button shows **an error message**.  
- Includes **retry logic** and resets automatically.  

---

## ⚙️ Installation & Deployment  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/AsifKamboh-COM/download-button.git
cd download-button
```

### 2️⃣ Install Dependencies (if needed)  
Since this is a **static HTML, CSS, and JS project**, no dependencies are required.  

### 3️⃣ Deploy on **Vercel**  
Make sure you have [Vercel CLI](https://vercel.com/download) installed:  
```sh
npm install -g vercel
```
Then deploy your project:  
```sh
vercel
```
🌐 **Your project will be live instantly!**  

---

## 💡 Usage Instructions  

1️⃣ **Open the webpage**: [Click Here](https://download-button-three.vercel.app/)  
2️⃣ Click on the **Download Button**.  
3️⃣ The **spinner** will appear while processing.  
4️⃣ File starts downloading automatically.  
5️⃣ **Download counter** updates dynamically.  

---

## 📝 Customization  

### 🎨 **Change Button Styles**  
You can modify the styles in `index.html` inside the `<style>` section.  

For example, change the **gradient color**:  
```css
:root {
    --primary-gradient: linear-gradient(135deg, #ff6b6b 0%, #ffb400 50%, #ffeb3b 100%);
}
```

### 📥 **Change Download Link**  
🔗 Modify the **href** inside the JavaScript code in `index.html`:  
```js
downloadLink.href = 'YOUR_FILE_DOWNLOAD_LINK_HERE';
```

---

## 📜 License  
This project is licensed under **GPL-3.0**.  
See the full license details in the [LICENSE](./LICENSE) file.  

---

## 👨‍💻 Author  
Developed with ❤️ by **Asif Kamboh** 😎  
Follow me for more amazing projects! 

---

## 🏆 Contributing  

🤝 Contributions are welcome!  

1️⃣ Fork the repository  
2️⃣ Make changes  
3️⃣ Submit a pull request  

👥 Let's build something amazing together!
