# Beautiful Tier List Maker

A web-based drag-and-drop **Tier List Maker** designed to let you create stunning tier lists—complete with images and emojis—with lightning-fast simplicity and a sleek, responsive interface. Perfect for gamers, content creators, educators, and anyone who loves ranking their favorites! Download it to run locally, serve it via a web server, or try a live version at [Picopixl.com](https://www.picopixl.com/tools/tier_list_maker.html)!

![image](https://github.com/user-attachments/assets/a8caa571-dcbf-48dd-a9be-9b34148bd563)

---

## 🌟 Features

* **Intuitive Drag & Drop**: Easily drag items (images or emoji placeholders) from the item pool into any tier row.
* **Customizable Tiers**: Edit tier labels (S, A, B, C, D, E, F) and show/hide tiers in the Properties panel.
* **Upload Images**: Bulk-upload images directly via drag-and-drop or the Upload Images button.
* **Live Preview**: See your tier list come to life in real-time with smooth animations and responsive design.
* **Light & Dark Themes**: Toggle between light and dark modes to match your style or presentation.
* **Export to PNG**: Export your tier list as an image (currently demoing via a canvas—full export functionality available with html2canvas integration).
* **Reset & Sample Items**: Reset everything back to default with a single click, or experiment with provided sample items (emoji icons).

---

## 🚀 Getting Started

### Prerequisites

This is a **purely front-end** application—no server or build tools required. All you need is a modern web browser (Chrome, Firefox, Safari, Edge).

### Installation

1. **Clone or download** this repository:

   ```bash
   git clone https://github.com/your-username/beautiful-tier-list-maker.git
   cd beautiful-tier-list-maker
   ```

2. **Open** the HTML file in your browser:

   * Double-click `tier_list_maker.html`, **OR**
   * Serve it via a simple HTTP server for full drag-and-drop support:

     ```bash
     # Python 3
     python3 -m http.server 8000

     # In your browser:
     http://localhost:8000/tier_list_maker.html
     ```

---

## 🎨 Usage

1. **Add Items**

   * Click **Upload Images** or drag images onto the "Item Pool" area to add your own icons.
   * By default, sample emoji items are already loaded for quick testing.

2. **Arrange Tiers**

   * Drag items from the item pool into any tier to assign them.
   * Items can be moved between tiers or returned to the pool at any time.

3. **Customize Tiers & Titles**

   * Click the **Properties** ⚙️ button to show/hide tiers, and toggle between light and dark themes.
   * Click on tier labels (e.g., "S", "A") or title/subtitle text to edit them inline.

4. **Export**

   * Click **Export as PNG** to download your tier list as an image.
   * *Note*: For full export fidelity, include the [html2canvas](https://html2canvas.hertzen.com/) library in `index.html` and adjust the `exportTierList()` function.

5. **Reset**

   * Use the 🔄 **Reset All** button to clear all items and tier assignments, and restore default labels.

---

## 💻 Customization & Development

* **Add Libraries**: Integrate external libraries (e.g., html2canvas) by including their CDN or local scripts.
* **Styling**: All styles are in the `<style>` block—feel free to extract them to a separate CSS file or customize gradients, fonts, and animations.
* **Extend Functionality**: Modify the script to support additional features such as saving/loading lists, custom export dimensions, or collaborative editing.

---

## 🤝 Contributing

Contributions are welcome! To propose bug fixes, enhancements, or new features:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/my-feature`).
3. Commit your changes (`git commit -m "Add my awesome feature"`).
4. Push to the branch (`git push origin feature/my-feature`).
5. Open a Pull Request.

Please ensure your code follows the existing style and includes clear documentation.

---

## 📄 License

This project is distributed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

*Enjoy ranking your favorites!* 🎉
