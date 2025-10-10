| [Home Page](https://mcorliss7239.github.io/corliss-dataviz-portfolio/) | [Visualizing Government Debt](visualizing-government-debt) | [Critique by Design](critique-by-design) | [Final Project I](final-project-part-one) | [Final Project II](final-project-part-two) | [Final Project III](final-project-part-three) | [More Data Visualizations](More-Data-Visualizations) | [Project Datasets](Project-Data-Sets)

# Visualizing Government Debt

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Visualizing Government Debt</title>
</head>
<body>
  
  <!-- First Dashboard -->
  <div class='tableauPlaceholder' id='viz1757284170399' style='position: relative; margin-bottom:40px;'>
    <noscript>
      <a href='#'>
        <img alt='Dashboard 1' src='https://public.tableau.com/static/images/Ta/Tableauwork_17572840558060/Dashboard1/1_rss.png' style='border: none' />
      </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='Tableauwork_17572840558060/Dashboard1' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https://public.tableau.com/static/images/Ta/Tableauwork_17572840558060/Dashboard1/1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='en-US' />
      <param name='filter' value='publish=yes' />
    </object>
  </div>

  <!-- Second Dashboard -->
  <div class='tableauPlaceholder' id='viz1757424597519' style='position: relative'>
    <noscript>
      <a href='#'>
        <img alt='Dashboard 2' src='https://public.tableau.com/static/images/De/Debt-to-GDPTrends/Dashboard1/1_rss.png' style='border: none' />
      </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='Debt-to-GDPTrends/Dashboard1' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https://public.tableau.com/static/images/De/Debt-to-GDPTrends/Dashboard1/1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='en-US' />
      <param name='filter' value='publish=yes' />
    </object>
  </div>

  <!-- Load and size both dashboards -->
  <script type='text/javascript'>
    function initViz(divId, widthLarge, heightLarge, heightSmall) {
      var divElement = document.getElementById(divId);
      var vizElement = divElement.getElementsByTagName('object')[0];
      if (divElement.offsetWidth > 800) {
        vizElement.style.width = widthLarge;
        vizElement.style.height = heightLarge;
      } else if (divElement.offsetWidth > 500) {
        vizElement.style.width = widthLarge;
        vizElement.style.height = heightLarge;
      } else {
        vizElement.style.width = '100%';
        vizElement.style.height = heightSmall;
      }
      var scriptElement = document.createElement('script');
      scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
      vizElement.parentNode.insertBefore(scriptElement, vizElement);
    }

    // Initialize both dashboards
    initViz('viz1757284170399', '1000px', '827px', '727px');
    initViz('viz1757424597519', '1000px', '827px', '727px');
  </script>

</body>
</html>
