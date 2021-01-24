# Работа АЭС в России

<div id="html1" markdown="0">
<div id="chart_vega" markdown="0"></div>

<script type="text/javascript" markdown="0">
  var spec = "chart.json";
  var opt = { actions: {export: true, source: false, compiled: false, editor: false}};
  vegaEmbed('#chart_vega', spec, opt).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view
  }).catch(console.error);
</script></div>

### О приложении

Данные по работе АЭС собраны с сайта [Росэнергоатома](https://www.rosenergoatom.ru/).

Данное приложение использует библиотеку [Vega](https://vega.github.io/).

&copy; 2021 [Геннадий Лоскутов](https://twitter.com/binxs_se)
