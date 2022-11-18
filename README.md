# html-repo
for learning html from zero

google source code 

<!doctype html>
<html dir="ltr" lang="es">
  <head>
    <meta charset="utf-8">
    <title>Nueva pestaña</title>
    <style>
      body {
        background: #353535;
        margin: 0;
      }

      #backgroundImage {
        border: none;
        height: 100%;
        pointer-events: none;
        position: fixed;
        top: 0;
        visibility: hidden;
        width: 100%;
      }

      [show-background-image] #backgroundImage {
        visibility: visible;
      }
    </style>
  </head>
  <body>
    <iframe id="backgroundImage" src="chrome-untrusted://new-tab-page/custom_background_image?url=https%3A%2F%2Flh4.googleusercontent.com%2Fproxy%2FgdKMsKqzMFQ1xEVJf9lNNfL7pw_HG3DaHZij1yJPHGPLQYzY_FXqVrSsC0Q2VK49HPML25NGCls545UIGYmTs6y11TAXtLcKAv_HmKA%3Dw3840-h2160-p-k-no-nd-mv"></iframe>
    <ntp-app></ntp-app>
    <script type="module" src="new_tab_page.js"></script>
    <link rel="stylesheet" href="chrome://resources/css/text_defaults_md.css">
    <link rel="stylesheet" href="chrome://theme/colors.css?sets=ui,chrome">
    <link rel="stylesheet" href="shared_vars.css">
  </body>
</html>
