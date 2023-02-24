<!--# DarkMode_and_LightMode-->
<!--Dark Theme and Light Theme-->

<!--HTML Code-->

<head>
  <meta name="color-scheme" content="light">
</head>
    <body>
        <select id="theme" onchange="switchTheme()">
            <option value="Light">Light</option>
            <option value="dark">Dark</option>
        </select>
    </body>
    
    
    <!--JS Code-->
function switchTheme(){
        const theme =
document.getElementById("theme").value;
        document.getElementsByTagName("meta")
[0].content = theme;
}
