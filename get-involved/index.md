---
title: Get Involved
description: Practical ways to support the campaign, contact decision-makers, and share information about the multimodal pathway proposal.
permalink: /get-involved/
section_title: Get Involved
section_url: /get-involved/
---

<figure>
  <img src="{{ '/assets/images/Multimodal_pathway_get_involved.png' | relative_url }}" alt="Get involved - make your voice heard">
</figure>

### Contact Alto

- Contact [Alto](https://www.altotrain.ca/en/public-consultation).
  - Public consultations closed on April 24th, 2026. Additional consultations are anticipated in the coming months as the project progresses.

### Contact elected officials

<p>
  You can <a href="{{ 'assets/docs/take-action/letter.txt' | relative_url }}" download="letter.txt">download a suggested email here</a>.
</p>

- Contact the [Federal Minister of Transportation Steven MacKinnon](https://www.ourcommons.ca/Members/en/Steven-MacKinnon(88468))
- Contact the [Eastern Ontario Warden's Council](https://eowc.org/contact-us/). 
  - The Wardens are responsible for the counties in Eastern Ontario (Frontenac, Haliburton, Hastings, Kawartha Lakes, Lanark, Leeds and Grenville, Lennox and Addington, Northmberland, Peterborough, Prescott Russell, Prince Edward, Renfrew and Stormont, Dundas, Glengarry)
- Contact your Federal MP: 
  - [Ontario MPs](https://www.ourcommons.ca/members/en/search?province=ON)
  - [Quebec MPs](https://www.ourcommons.ca/members/en/search?province=QC)
- Contact your Provinical Representative:
  - [Ontario MPPs](https://www.ola.org/en/members/current/contact-information)
  - [Quebec MNAs](https://www.assnat.qc.ca/en/deputes/index.html)
- Contact your Mayor and City Councillor
  - [Toronto](https://www.toronto.ca/city-government/council/members-of-council/)
  - [Ottawa](https://ottawa.ca/en/city-hall/mayor-and-city-councillors)
  - [Laval](https://www.laval.ca/vie-democratique/hotel-de-ville-personnes-elues/membres-conseil-municipal/)
  - [Montreal](https://montreal.ca/en/elected-officials)
  - [Quebec](https://www.ville.quebec.qc.ca/apropos/gouvernance/conseil-municipal/membres.aspx)

## Download our backgrounder
  <p>Download our <a href="{{ 'assets/docs/take-action/Alto Multimodal Pathway Backgrounder 3.pdf' | relative_url }}" download="Alto Multimodal Pathway Backgrounder 3.pdf">1-page backrounder</a> and share with your friends, family and decision makers.</p>

<div class="share-block">
  <h2>Share this page</h2>
  <p>If you found this page useful, please share it with others.</p>

  <button type="button" class="button button-secondary" id="share-page-button">Share this page</button>

</div>

<script>
document.getElementById('share-page-button')?.addEventListener('click', async () => {
  const shareData = {
    url: window.location.href
  };

  if (navigator.share) {
    try {
      await navigator.share(shareData);
    } catch (err) {
      console.log("Share cancelled or failed", err);
    }
  } else {
    navigator.clipboard.writeText(window.location.href);
    alert("Page link copied to clipboard.");
  }
});
</script>

<div class="callout">
  <h2>Need a quick answer first?</h2>
  <p>The FAQ gives concise answers to the questions visitors are most likely to ask before acting.</p>
  <p><a class="button button-primary" href="{{ '/faq/' | relative_url }}">Read the FAQ</a></p>
</div>
