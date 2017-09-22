---
layout: page
title: Non-profit
permalink: /nonprofit/
---

I've worked with [San Diego Regional Data Library](https://www.sandiegodata.org){:target="_blank"} on several projects for civic and non-profit groups. Read below for details.

---
#### Consumer Advocates for RCFE* Reform (CARR)
*Residential Care Facility for the Eldery

[CARR](https://www.rcfereform.org/){:target="_blank"} approached us for a data-driven answer to the question: what parts of San Diego County are or will be underserved by their RCFE capacity given current and projected senior populations? With this info, CARR would lobby policymakers to dedicate resources to mitigate the effects of RCFE shortfalls in their areas. They could, for example, dedicate funds to concierge medical services so that seniors might remain at home close to loved ones rather than relocate hours away to the nearest affordable RCFE.

CARR needed a visualization containing a message that could be effectively delivered to a non-technical audience in a ten minute pitch. To this end, I did some transformations on available RCFE and census data to generate a "CARR score" for each subregional area (SRA) in the county. The CARR score is derived by first computing "heads per bed" for each SRA - the number of seniors divided by the licensed RCFE capacity - and weighting these figures by the senior populations of the SRAs so sparsely populated areas would not have outsize influence in the visualization. The "weighted heads per bed" values were then log-transformed to compress their range, yielding final CARR scores which should be easily digestible for non-technical audiences. A high CARR score, then, indicates _both_ a large senior population _and_ a low ratio of beds to seniors. The below interactive visualisation should make it easy to convey the urgency of RCFE shortfall to officials in South Bay, for example.

<body>
<div class='tableauPlaceholder' id='viz1505969786994' style='position: relative'><noscript><a href='#'><img alt='Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CA&#47;CARRScore-SanDiegoSRAs&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='site_root' value='' /><param name='name' value='CARRScore-SanDiegoSRAs&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CA&#47;CARRScore-SanDiegoSRAs&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1505969786994');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
</body>

