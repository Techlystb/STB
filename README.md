# STB


<script type='text/javascript'>
//<![CDATA[

// CSS Files
const styles = [
  "https://cdn.jsdelivr.net/gh/Techlystb/assets/css/style.min.css",
  "https://cdn.jsdelivr.net/gh/Techlystb/assets/css/file1.min.css"
];

styles.forEach(href => {
  const link = document.createElement("link");
  link.rel = "stylesheet";
  link.href = href;
  document.head.appendChild(link);
});

// JS Files
const scripts = [
  "https://cdn.jsdelivr.net/gh/Techlystb/assets/js/ThemeChangerAuto.min.js",
  "https://cdn.jsdelivr.net/gh/Techlystb/assets/js/file2.js",
  "https://cdn.jsdelivr.net/gh/Techlystb/assets/js/file3.js",
  "https://cdn.jsdelivr.net/gh/Techlystb/assets@main/js/file1.min.js"
];

scripts.forEach(src => {
  const s = document.createElement("script");
  s.src = src;
  document.body.appendChild(s);
});

//]]>
</script>
