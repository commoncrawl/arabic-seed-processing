# Turning 30,000 Arabic domains into a better crawl
Code and data accompanying the work described in [this blog post](https://commoncrawl.org/blog/turning-30000-arabic-domains-into-a-better-crawl) to filter, geolocate and categorise a donation of Arabic seed domains.

## Contents
- `ArabicDomainQuality.xlsx`: The original data received from QCRI.
- `arabic_seeds.ipynb`: A notebook detailing the data processing and analysis.
- `crawl_lang_info.tsv`: Summarised language information for the domains found in the CC-MAIN-2026-{21,17,12} archives.
- `DomainQuality_Dashboard.ipynb`: Additional analysis of the quality of the pre-filtered domains, carried out by researchers at QCRI.

We use [uv](https://docs.astral.sh/uv/) to manage Python dependencies.

## Acknowledgements

Thank you to [Hamdy S. Hussein](https://elmi.hbku.edu.qa/en/persons/hamdy-soliman-mubarak-hussien/), [Dr. Kareem M. Darwish](https://kareemdarwish.com) and [Dr. Mohamed Ahmed Yassin Eltabakh](https://elmi.hbku.edu.qa/en/persons/mohamed-ahmed-yassin-eltabakh/) of the [Qatar Computing Research Institute](https://www.hbku.edu.qa/en/qcri) for providing the initial seed list, quality annotations and exploratory visualisations. These were created as part of the [Fanar Project](http://www.fanar.qa), an Arabic generative AI platform.
