---
title: Evidence
permalink: /evidence/
section_title: Evidence
section_url: /evidence/
---
<figure>
  <img src="{{ '/assets/images/Multimodal_pathway_evidence_wide_aspect.png' | relative_url }}" alt="Evidence based, source-backed">
</figure>

## F1 Bicycle Highway 
<figure>
  <img src="{{ '/assets/images/F1_Cycle_Highway_Antwerpen.png' | relative_url }}" alt="Man and woman cyclist on the F1 Cycle Highway. Copyright: Dienst Mobiliteit Provincie Antwerpen">
  <figcaption>The F1 Bicycle Highway. Copyright: Dienst Mobiliteit Provincie Antwerpen</figcaption>
</figure>
[Belgium’s F1 cycle highway](https://vb.nweurope.eu/projects/project-search/cycle-highways-innovation-for-smarter-people-transport-and-spatial-planning/news/f1-cycling-on-a-highway-along-a-railroad-line/) presents a strong real-world example of using a rail corridor for high-quality cycling infrastructure. 
- The route follows the railway between Antwerp and Mechelen, including the Amsterdam–Brussels high-speed line.
- Now carryies more than 4,000 cyclists per workday on its busiest sections. 
- The route has been progressively improved through priority changes at crossings and new cycling bridges alongside rail infrastructure, showing how a rail corridor can support both national transport and local active mobility at the same time.

## F3 Bicycle Highway
<figure>
  <img src="{{ '/assets/images/F3_Cycle_Highway.png' | relative_url }}" alt="Cyclist on the F3 Cycle Highway. Photo Credit: NEY Partners">
  <figcaption>The F3 Bicycle Highway. Photo credit: NEY Partners</figcaption>
</figure>

The [F3 Bicycle Highway](https://www.werkenaandering.be/en/working-on/cycling-infrastructure/f3-bicycle-highway)
 ([see also](https://ney.partners/project/infrastructure-cycle-highway-f3/))
- Belgium's F3 Cycling Highway follows an existing high-speed rail line, sharing many bridges and crossings to improve the directness and efficiency of the route.

## European Cycling Foundation TEN-T Position Paper
<figure>
  <img src="{{ '/assets/images/F1_Cycle_Highway_ECF.png' | relative_url }}" alt="A high speed train alongside the F1 Cycle Highway Photo Credit: ECF">
  <figcaption>The F1 Bicycle Highway beside the High-Speed Rail tracks. Photo credit: ECF</figcaption>
</figure>
[The European Cycling Federation](https://www.ecf.com/media/resources/2021/TEN-T_ECF_Position_Paper_2020-2.pdf) recommends that all major transport corridors (including rail) should systematically include cycling infrastructure — especially parallel routes and crossings — and this must be done at the planning stage, not retrofitted later. 
- Cycling is part of the core transport network and should be integrated alongside rail. 
- Cycle highways along TEN-T railroad lines… have already proven to be successful. 
- Many transport corridors already include service roads for maintenance or access. These can be reused for cycling at low cost. Design maintenance corridors once — use them twice.
- Safe, direct, connected and continuous routes are needed. Missing crossings or continuity can make cycling non-viable, even if infrastructure exists nearby. 
- Without a multimodal pathway being designed in early
  - corridors become barriers
  - existing trails can be destroyed
  - crossings become inadequate

## US Department of Transport. Rails with Trails: Lessons Learned
<figure>
  <img src="{{ 'assets\images\Schuylkill_River_Trail_Pennsylvania_Photo_Credit_Circuit_Trail_Coalition.png' | relative_url }}" alt="An adult and child cycle along a trail alongside a railway line with a freight train on it. Photo Credit: Circuit Trail Coalition">
  <figcaption>The Schuylkill River Trail in Pennsylvania. Photo credit: Circuit Trail Coalition</figcaption>
</figure>
[The U.S. Department of Transportation’s Rails-with-Trails: Lessons Learned](https://railroads.dot.gov/sites/fra.dot.gov/files/2021-06/Rails%20with%20Trails%20Best%20Practices%20and%20Lessons%20Learned.pdf) study demonstrates that trails adjacent to active rail lines are feasible and already exist in many jurisdictions, including alongside higher-speed passenger services. The study concludes that success depends on 
- early integration into corridor design
- including appropriate setbacks
- physical separation such as fencing
- carefully designed crossings
- close coordination with rail operators

When these principles are applied, rail-with-trail corridors can deliver significant public benefits—including improved safety through reduced trespassing, enhanced tourism and local economic activity, and better access for maintenance and emergency services—while maintaining safe and efficient rail operations.

<div class="share-block">
  <h2>Share this page</h2>
  <p>If you found this useful, please share it with others.</p>

  <button type="button" class="button button-secondary" id="share-page-button">Share this page</button>

</div>

<script>
document.getElementById('share-page-button')?.addEventListener('click', async () => {
  const shareData = {
    title: document.title,
    text: "Take a look at this page.",
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

