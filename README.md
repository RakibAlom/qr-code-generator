Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML``   # 🔳 QR Code Generator  A modern, feature-rich, and completely free QR Code Generator built with vanilla JavaScript and Tailwind CSS. Create professional, customizable QR codes for URLs, WiFi, contacts, payments, and more — directly in your browser with no registration required.  ![QR Code Generator](https://img.shields.io/badge/QR Code-Generator-purple?style=for-the-badge)  ![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)  ![Made With](https://img.shields.io/badge/made with-HTML/JS/Tailwind-blue?style=for-the-badge)  ## 🚀 Live Demo  **[Try it now →](https://rakibalom.com/tools/qr-code-generator)**  ## ✨ Features  ### 12+ QR Code Types Supported  | Type | Description | Use Case |  |------|-------------|----------|  | 🔗 **URL** | Website links | Marketing campaigns, product pages |  | 📝 **Text** | Plain text messages | Quick notes, quotes |  | 📶 **WiFi** | Network credentials | Guest access, cafes, offices |  | 📧 **Email** | Pre-filled emails | Contact forms, support requests |  | 📞 **Phone** | Direct dial numbers | Customer service, appointments |  | 💬 **SMS** | Text message templates | Marketing opt-ins, alerts |  | 👤 **vCard** | Digital business cards | Networking, contact sharing |  | 📍 **Location** | GPS coordinates | Events, store locations |  | 📅 **Event** | Calendar invitations | Conferences, meetings |  | 🌐 **Social** | Social media profiles | Follow buttons, influencer marketing |  | 📱 **App Store** | Mobile app links | App downloads |  | 💳 **Payment** | UPI, PayPal, Crypto | Contactless payments |  ### 🎨 Customization Options  - **Colors**: Custom foreground and background colors  - **Size**: Adjustable dimensions (150px - 350px)  - **Formats**: Export as PNG (raster) or SVG (vector)  - **Quality**: High-resolution output suitable for print  ### 🔒 Privacy & Security  - **Client-side generation** — Your data never leaves your browser  - **No server storage** — QR codes are generated locally using JavaScript  - **No registration required** — Use instantly without signing up  ### 📱 Responsive Design  - Fully responsive layout for desktop, tablet, and mobile  - Touch-friendly interface  - Optimized for all modern browsers  ## 🛠️ Technologies Used  - **HTML5** — Semantic markup with accessibility features  - **Tailwind CSS** — Utility-first styling with custom glassmorphism design  - **Vanilla JavaScript** — No frameworks, lightweight and fast  - **[QRCode.js](https://github.com/davidshimjs/qrcodejs)** — QR code generation library  - **Schema.org Structured Data** — SEO-optimized with JSON-LD  ## 🎯 SEO Optimizations  This tool includes comprehensive SEO features:  - ✅ Semantic HTML5 structure  - ✅ Schema.org markup (WebApplication, Article, FAQPage, BreadcrumbList)  - ✅ Open Graph and Twitter Card meta tags  - ✅ Canonical URLs and proper meta descriptions  - ✅ 800+ word SEO-optimized article content  - ✅ FAQ section with structured data  - ✅ Accessible ARIA labels and roles  - ✅ High-performance Core Web Vitals ready  ## 📦 Installation  ### Method 1: Direct Download  1. Download the `index.html` file  2. Open in any modern web browser  3. Start generating QR codes instantly  ### Method 2: Clone Repository  ```bash  git clone https://github.com/rakibalom/qr-code-generator.git  cd qr-code-generator  # Open index.html in your browser or serve with a local server   ``

### Method 3: Local Server (Recommended)

**bash**Copy

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   # Using Python  python -m http.server 8000  # Using Node.js  npx serve .  # Using PHP  php -S localhost:8000   `

Then visit http://localhost:8000

📝 Usage Guide
--------------

### Creating Your First QR Code

1.  **Select Type**: Choose from 12+ QR code types (URL, WiFi, vCard, etc.)
    
2.  **Enter Details**: Fill in the required information for your selected type
    
3.  **Customize**: Adjust colors and size to match your branding
    
4.  **Generate**: Click the "Generate QR Code" button
    
5.  **Download**: Save as PNG or SVG, or copy to clipboard
    

### Example: WiFi QR Code

Copy

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   Network Name: MyHomeWiFi  Password: SuperSecret123  Security: WPA/WPA2  → Scan to automatically connect guests to your network   `

### Example: vCard QR Code

Copy

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   First Name: John  Last Name: Doe  Phone: +1234567890  Email: john@example.com  → Scan to instantly save contact to phone   `

🎨 Customization Examples
-------------------------

### Brand Colors

**JavaScript**Copy

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   // Default purple gradient theme  Primary: #8b5cf6 (Violet)  Secondary: #3b82f6 (Blue)  Accent: #06b6d4 (Cyan)   `

### Custom QR Code Colors

*   **Foreground**: Any hex color (default: #000000)
    
*   **Background**: Any hex color (default: #ffffff)
    
*   **Best Practice**: Ensure high contrast for reliable scanning
    

🌟 Key Highlights
-----------------

**Table**Copy**FeatureBenefit**⚡ **Instant Generation**No loading screens, immediate results🆓 **100% Free**No watermarks, no limits, no hidden costs🔒 **Privacy First**Zero data collection or tracking📱 **Mobile Optimized**Works perfectly on smartphones🖨️ **Print Ready**High-resolution SVG for professional printing🌐 **Universal Scanning**Compatible with all QR code readers

🧪 Browser Compatibility
------------------------

**Table**Copy**BrowserVersionStatus**Chrome80+✅ Fully SupportedFirefox75+✅ Fully SupportedSafari13+✅ Fully SupportedEdge80+✅ Fully SupportedOpera67+✅ Fully SupportedMobile BrowsersLatest✅ Fully Supported

📁 Project Structure
--------------------

Copy

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   qr-code-generator/  ├── index.html          # Main application (single file)  ├── README.md           # This file  ├── LICENSE             # MIT License  └── assets/      └── favicon.svg     # Custom QR code favicon   `

🤝 Contributing
---------------

Contributions are welcome! Please feel free to submit a Pull Request.

### Ways to Contribute

*   🐛 Report bugs or issues
    
*   💡 Suggest new features or QR code types
    
*   📝 Improve documentation
    
*   🎨 Enhance UI/UX design
    
*   🌐 Add translations
    

### Development Guidelines

1.  Fork the repository
    
2.  Create your feature branch (git checkout -b feature/AmazingFeature)
    
3.  Commit your changes (git commit -m 'Add some AmazingFeature')
    
4.  Push to the branch (git push origin feature/AmazingFeature)
    
5.  Open a Pull Request
    

📄 License
----------

This project is licensed under the MIT License — see the [LICENSE](https://www.kimi.com/chat/LICENSE) file for details.Copy

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   MIT License  Copyright (c) 2026 Rakib Alom  Permission is hereby granted, free of charge, to any person obtaining a copy  of this software and associated documentation files (the "Software"), to deal  in the Software without restriction, including without limitation the rights  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  copies of the Software, and to permit persons to whom the Software is  furnished to do so, subject to the following conditions:  The above copyright notice and this permission notice shall be included in all  copies or substantial portions of the Software.   `

🙏 Acknowledgments
------------------

*   [QRCode.js](https://github.com/davidshimjs/qrcodejs) — The QR code generation library
    
*   [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework
    
*   [Inter Font](https://rsms.me/inter/) — Clean, modern typeface
    
*   [Heroicons](https://heroicons.com/) — Beautiful SVG icons
    

📞 Contact & Support
--------------------

*   **Website**: [rakibalom.com](https://rakibalom.com/)
    
*   **Email**: [contact@rakibalom.com](mailto:contact@rakibalom.com)
    
*   **Twitter**: [@rakibalom](https://twitter.com/rakibalom)
    
*   **Issues**: [GitHub Issues](https://github.com/rakibalom/qr-code-generator/issues)
    

README Features Included:
-------------------------

### 🎯 **Structure & Organization**

*   Clear hierarchy with emoji visual cues
    
*   Table of contents through section headers
    
*   Comprehensive feature comparison tables
    

### 📝 **Content Sections**

*   **Features**: Detailed breakdown of all 12 QR code types
    
*   **Tech Stack**: Technologies and libraries used
    
*   **SEO**: Highlights optimization features
    
*   **Installation**: Multiple setup methods
    
*   **Usage Guide**: Step-by-step instructions with examples
    
*   **Browser Support**: Compatibility matrix
    
*   **Contributing**: Guidelines for open-source contribution
    

### 🎨 **Visual Elements**

*   Badges for license, tech stack, and status
    
*   Tables for type comparison and browser support
    
*   Code blocks for technical examples
    
*   Centered footer with links
    

### 🔧 **Technical Details**

*   Single-file architecture explanation
    
*   Client-side generation emphasis
    
*   Privacy-first approach documentation
    
*   Performance optimization notes
    

### 📋 **Professional Standards**

*   MIT license template
    
*   Contact information
    
*   Acknowledgments and credits
    
*   GitHub-specific formatting (issues, PRs)