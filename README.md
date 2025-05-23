# PortSwigger Web Security Labs Solutions

## 📚 Overview

This repository contains detailed documentation and solutions for various web security labs from PortSwigger Web Security Academy. The focus is primarily on Cross-Site Scripting (XSS) vulnerabilities, including Reflected, Stored, DOM-based, and Blind XSS scenarios.

## 🎯 Purpose

The main objectives of this repository are:
- Document and explain different types of XSS vulnerabilities
- Provide detailed walkthroughs of PortSwigger lab solutions
- Serve as a learning resource for web security professionals
- Demonstrate various exploitation techniques and prevention methods

## 📁 Repository Structure

### [PortSwigger Reflected/](PortSwigger%20Reflected/)
- [1. into attribute with angle brackets HTML-encoded EN.md](PortSwigger%20Reflected/1.%20into%20attribute%20with%20angle%20brackets%20HTML-encoded%20EN.md)
- [2. into a JavaScript string with angle brackets HTML encoded EN.md](PortSwigger%20Reflected/2.%20into%20a%20JavaScript%20string%20with%20angle%20brackets%20HTML%20encoded%20EN.md)
- [3. into HTML context with most tags and attributes blocked EN.md](PortSwigger%20Reflected/3.%20into%20HTML%20context%20with%20most%20tags%20and%20attributes%20blocked%20EN.md)
- [4. into HTML context with all tags blocked except custom ones EN.md](PortSwigger%20Reflected/4.%20into%20HTML%20context%20with%20all%20tags%20blocked%20except%20custom%20ones%20EN.md)
- [5. with some SVG markup allowed EN.md](PortSwigger%20Reflected/5.%20with%20some%20SVG%20markup%20allowed%20EN.md)
- [6. in canonical link tag EN.md](PortSwigger%20Reflected/6.%20in%20canonical%20link%20tag%20EN.md)
- [7. into a JavaScript string with single quote and backslash escaped EN.md](PortSwigger%20Reflected/7.%20into%20a%20JavaScript%20string%20with%20single%20quote%20and%20backslash%20escaped%20EN.md)
- [8. into a JavaScript string with angle brackets and double quotes HTML-encoded and single quotes escaped EN.md](PortSwigger%20Reflected/8.%20into%20a%20JavaScript%20string%20with%20angle%20brackets%20and%20double%20quotes%20HTML-encoded%20and%20single%20quotes%20escaped%20EN.md)
- [9. into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped EN.md](PortSwigger%20Reflected/9.%20into%20a%20template%20literal%20with%20angle%20brackets%2C%20single%2C%20double%20quotes%2C%20backslash%20and%20backticks%20Unicode-escaped%20EN.md)

### [PortSwigger Dom/](PortSwigger%20Dom/)
- [2. DOM XSS in innerHTML sink using source location.search.md](PortSwigger%20Dom/2.%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20location.search.md)
- [3. DOM XSS in jQuery anchor href attribute sink using location.search source.md](PortSwigger%20Dom/3.%20DOM%20XSS%20in%20jQuery%20anchor%20href%20attribute%20sink%20using%20location.search%20source.md)
- [4. DOM XSS in jQuery selector sink using a hashchange event.md](PortSwigger%20Dom/4.%20DOM%20XSS%20in%20jQuery%20selector%20sink%20using%20a%20hashchange%20event.md)
- [5. DOM XSS in document.write sink using source location.search inside a select element.md](PortSwigger%20Dom/5.%20DOM%20XSS%20in%20document.write%20sink%20using%20source%20location.search%20inside%20a%20select%20element.md)
- [6. DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded.md](PortSwigger%20Dom/6.%20DOM%20XSS%20in%20AngularJS%20expression%20with%20angle%20brackets%20and%20double%20quotes%20HTML-encoded.md)
- [7. Reflected DOM XSS.md](PortSwigger%20Dom/7.%20Reflected%20DOM%20XSS.md)
- [8. Stored DOM XSS.md](PortSwigger%20Dom/8.%20Stored%20DOM%20XSS.md)

### [PortSwigger Stored/](PortSwigger%20Stored/)
- [1. Stored XSS into anchor href attribute with double quotes HTML-encoded.md](PortSwigger%20Stored/1.%20Stored%20XSS%20into%20anchor%20href%20attribute%20with%20double%20quotes%20HTML-encoded.md)
- [2. Stored XSS into `onclick` event with angle brackets and double quotes HTML-encoded and single quotes and backslash escaped.md](PortSwigger%20Stored/2.%20Stored%20XSS%20into%20%60onclick%60%20event%20with%20angle%20brackets%20and%20double%20quotes%20HTML-encoded%20and%20single%20quotes%20and%20backslash%20escaped.md)

### [PortSwigger Blind/](PortSwigger%20Blind/)
- [1. Exploiting cross-site scripting to steal cookies.md](PortSwigger%20Blind/1.%20Exploiting%20cross-site%20scripting%20to%20steal%20cookies.md)
- [2. Exploiting cross-site scripting to capture passwords.md](PortSwigger%20Blind/2.%20Exploiting%20cross-site%20scripting%20to%20capture%20passwords.md)

## 📝 Documentation Format

Each solution file follows a consistent structure:
1. General Information
   - Lab Link
   - Solution Date
   - Vulnerability Type

2. Lab Description
   - Scenario Overview
   - Technical Context

3. Solution Walkthrough
   - Initial Analysis
   - Exploitation Steps
   - Payload Explanation

4. Technical Details
   - Code Examples
   - Security Implications
   - Prevention Methods

## 🛠️ Tools Used

- Burp Suite
- Web Browser Developer Tools

## ⚠️ Disclaimer

This repository is intended for educational purposes only. The techniques and solutions documented here should only be used in controlled environments with proper authorization. Always follow ethical hacking guidelines and respect privacy and security laws.

## 📚 Additional Resources

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [OWASP XSS Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
- [MDN Web Security Documentation](https://developer.mozilla.org/en-US/docs/Web/Security)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details. 