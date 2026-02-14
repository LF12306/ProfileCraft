# 🌈 Cheese Profile Craft
### [中文](./document/README.zh-CN.md) / [日本語](./document/README.ja-JP.md) / [한국어](./document/README.ko-KR.md)

>A note from the developer, "chizukuo" (小芝士)!  
>The name "chizu" (cheese,芝士, zhī shì) is a fun pun on the Chinese phrase "This is" (这是, zhè shì).  
>So, the name is a playful greeting: "From chizukuo, this is a profile card editor!"

Cheese Profile Craft is a modern editor for creating "profile cards" (kuò liè tiáo), popular in Chinese online communities for finding friends with shared interests.  
It lets you freely edit text, customize theme colors, upload avatars and QR codes, manage dynamic content blocks, and export your creation as standalone HTML or high-res PNG — perfect for showcasing personality and social sharing.

---

## 👉 Try it Live! ([GitHub Pages Deployment](https://chizukuo.github.io/ProfileCraft/))



## 📌 Features
- 🖋️ **Live Rich Text Editing**  
  What you see is what you get. Click and type.  
  Supports **bold**, *italic*, ~~strikethrough~~, <u>underline</u>.

- 🎨 **Custom Themes**  
  Pick a primary color and the theme auto-adjusts for stylish consistency.

- 🖼️ **Instant Avatar & QR Code Updates**  
  Upload your own avatar (stored locally as Base64).  
  Paste a new link to regenerate your QR code instantly.

- 🗂️ **Dynamic Content Blocks**  
  Add cards from templates.  
  Add blocks like paragraphs, tag clouds, favorite info.  
  Hover to delete cards, blocks, or individual tags easily.

- 💾 **Auto-Save**  
  Changes auto-save in browser [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage). Safe even on refresh.

- 📤 **Multiple Export Options**  
  Export your finished card as standalone HTML or crisp PNG.  
  One-click reset to default template.

- 📱 **Mobile-First Design**  
  Responsive design with collapsible toolbar for smooth mobile experience.

---

## 🛠️ Getting Started
- 🚀 **Access Online**  
  👉 [https://chizukuo.github.io/ProfileCraft/](https://chizukuo.github.io/ProfileCraft/)

- ✨ **Editing Guide**  
  - Click to edit text.  
  - Highlight to format.  
  - Change theme color via sidebar/toolbar.  
  - Add/delete cards and blocks freely.

---

## 🏠 Local Deployment

### Option 1: npm (Development)
```bash
git clone https://github.com/LF12306/ProfileCraft.git
cd ProfileCraft
npm install
npm run dev
```
Open http://localhost:5173

### Option 2: npm (Production Preview)
```bash
npm run start
```
Open http://localhost:4173

### Option 3: Docker
```bash
docker compose up -d
```
Open http://localhost:3000

---

## 📦 Exporting
- Export HTML or PNG from the top toolbar.  
- One-click reset to default.

---

## ⚙️ Tech Stack

- Framework: [React](https://reactjs.org/)  
- Language: [TypeScript](https://www.typescriptlang.org/)  
- Build Tool: [Vite](https://vitejs.dev/)  
- State Management: [React Context API](https://reactjs.org/docs/context.html)  
- Styling: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) + [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)  
- Icons: [Lucide React](https://lucide.dev/)

### Core Libraries
- [html2canvas](https://github.com/niklasvh/html2canvas) — export PNG images  
- [qrcode.react](https://github.com/zpao/qrcode.react) — QR code generator

---

## ⚠️ Heads-Up
- Data is stored locally in your browser's [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).  
- Clearing your cache deletes saved data — back up if needed.  
- [html2canvas](https://github.com/niklasvh/html2canvas) may have trouble with complex CSS.  
- Exported HTML requires internet for web fonts.

Enjoy crafting your unique profile card! 🎉