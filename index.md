<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

  </head>

  <body>
  <p style="text-align: center;"><span style="color: #008000;"><strong>SELECT YOUR PLATFORM BELOW:</strong></span></p>
    <header>
      <div class="container">

        <section id="downloads">
          {% if site.show_downloads %}
          {% endif %}
          <p><a href="https://petesoelite.github.io/xbox-retailmode-apps/"><img style="display: block; margin-left: auto; margin-right: auto;" src="./img/xbox.png" alt="" /></a> </p>
        </section>
      </div>
    </header>

    <div class="container">
      <section id="main_content">
        {{ content }}
      </section>
    </div>
  </body>
</html>


<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: site.github.build_revision | relative_url }}">

  </head>

  <body>

    <header>
      <div class="container">

        <section id="downloads">
          {% if site.show_downloads %}
          {% endif %}
          <p style="text-align: center;"><img src="./img/ps.png" alt="" /></p>
        </section>
      </div>
    </header>

    <div class="container">
      <section id="main_content">
        {{ content }}
      </section>
    </div>
  </body>
</html>
