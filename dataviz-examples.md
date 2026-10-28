| [home page](https://chenanchien.github.io/kevin-chien-portfolio/) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Data visualization examples

## OECD General Government Debt-to-GDP Ratio, 1995–2019 (Tableau)

This highlight table compares general government debt as a percentage of GDP across 34 OECD countries from 1995 to 2019. Countries are sorted by their average debt-to-GDP ratio over the period. The diverging color scale is centered at 100%: orange cells show years when a country's government debt was larger than its GDP, and blue cells show years below that line. Colombia was excluded because the dataset only had a few years of data for it.

<div class='tableauPlaceholder' id='vizOECDDebt1995' style='position: relative'><noscript><a href='#'><img alt='OECD Government Debt-to-GDP Ratio, 1995-2019' src='https://public.tableau.com/static/images/OE/OECD_Government_Debt/OECDGovernmentDebt-to-GDPRatio1995-2019/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OECD_Government_Debt&#47;OECDGovernmentDebt-to-GDPRatio1995-2019' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECD_Government_Debt&#47;OECDGovernmentDebt-to-GDPRatio1995-2019&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

<script type='text/javascript'>
var divElement = document.getElementById('vizOECDDebt1995');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

[View on Tableau Public](https://public.tableau.com/app/profile/kevin.chien2383/viz/OECD_Government_Debt/OECDGovernmentDebt-to-GDPRatio1995-2019)

_Source: OECD (2020), General government debt (indicator), [https://data.oecd.org/gga/general-government-debt.htm](https://data.oecd.org/gga/general-government-debt.htm)._

## Ireland Cut Its Debt After 2008. Greece and the U.S. Never Did (Tableau)

This dumbbell chart follows general government debt (% of GDP) for the United States and nine European countries at three points: 2007, before the global financial crisis (gray); the highest level each country reached between 2008 and 2019 (orange); and 2019 (navy). The United States is shown on its own row at the top so it can be compared with the European countries below it, which are sorted by how much their debt grew between 2007 and 2019. Ireland, the Netherlands and Germany brought their debt back down after the peak, while Greece, France and the United States were still at or near their highest level in 2019. The dashed line marks debt equal to 100% of GDP.

<div class='tableauPlaceholder' id='vizOECDDebtCrisis' style='position: relative'><noscript><a href='#'><img alt='Ireland Cut Its Debt After 2008. Greece and the U.S. Never Did' src='https://public.tableau.com/static/images/OE/OECD_Government_Debt/DebtBeforeAtPeakandAfterthe2008Crisis/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OECD_Government_Debt&#47;DebtBeforeAtPeakandAfterthe2008Crisis' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECD_Government_Debt&#47;DebtBeforeAtPeakandAfterthe2008Crisis&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

<script type='text/javascript'>
var divElement = document.getElementById('vizOECDDebtCrisis');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

[View on Tableau Public](https://public.tableau.com/app/profile/kevin.chien2383/viz/OECD_Government_Debt/DebtBeforeAtPeakandAfterthe2008Crisis)

_Source: OECD (2020), General government debt (indicator), [https://data.oecd.org/gga/general-government-debt.htm](https://data.oecd.org/gga/general-government-debt.htm)._
