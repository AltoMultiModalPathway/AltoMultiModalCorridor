---
title: Why It Matters
description: Why adding a multimodal pathway matters for connectivity, local benefit, tourism, active transportation, and long-term public value.
permalink: /the-case/why-it-matters/
section_title: The Case
section_url: /the-case/
---
<figure>
  <img src="{{ '/assets/images/Multimodal_pathway_why_it_matters.png' | relative_url }}" alt="Image showing the high speed rail line with train and adjacent multimodal corridor with cyclists, pedestrians, joggers, and people pushing strollers. There is a small village with stores and a cafe near to the trail. Image text: Local Use & Quality of Life: the trail offers a place to walk, bike and enjoy the landscape, fostering active, healthy communities. Tourism & Economy: A trail can link communities, support regional tourism, and bring more visitors to local shops and services. Active Transportation: A trail provides safe, direct routes for cycling and walking, encouraging sustainable travel. Connectivity & Barrier Prevention: A trail can prserve access or create new links for communities where the rail line might otherwise divide them. Integrating public pathways during design is more practical and cost effective than retrofitting later.">
</figure>

Major infrastructure corridors like Alto do more than move people between cities. They shape 
- how land is used
- how communities connect
- how public space is experienced for generations

As such, the conversation around Alto is not only about travel times or economic competitiveness—it is also about what kind of corridor is being created, and who benefits from it.

A multimodal pathway is worth considering because it offers a way to extend the corridor’s public value beyond rail users alone. 

High-speed rail primarily serves intercity travellers, but the corridor itself passes through and alongside many communities. A parallel pathway could allow those communities to interact with and benefit from the corridor directly, rather than experiencing it only as infrastructure that passes through.

From a community perspective, the questions are practical
- Does the corridor improve access? 
- Does it add something meaningful to daily life? 
- Could it support recreation, active transportation or local economic activity? 

A pathway helps answer those questions by creating visible, everyday value—a place people can use, not just pass by. It can support local mobility, connect existing trail networks, and contribute to tourism and regional identity, particularly in rural and smaller urban areas.

There is also an important spatial consideration. New rail corridors—especially high-speed rail—are typically designed as controlled-access, fenced environments for safety and operational reasons. Without careful planning, this can introduce new barriers across landscapes that were previously permeable. 

Considering a pathway alongside the corridor creates an opportunity to maintain or enhance connectivity, ensuring that the corridor links places rather than unintentionally dividing them.

Timing matters as well. It is generally more practical and cost-effective to consider complementary uses—such as pathways, crossings, and connections—during the planning and design phase, when corridor geometry, access points, and interfaces are still flexible. Retrofitting these elements later can be more complex, more expensive, and less effective. Early consideration does not guarantee implementation, but it keeps the option open and allows it to be evaluated alongside other corridor priorities (see the [evidence section]({{ '/evidence/research/' | relative_url }})).

Importantly, this is not about changing Alto’s core purpose. The primary function of the project remains high-speed rail. 

Rather, it is about asking whether the corridor can also deliver additional public benefit at the same time, in a way that is proportionate, feasible, and responsive to local context.

In that sense, the multimodal pathway concept is part of a broader public-interest conversation: how a major national investment can be designed not only to move people efficiently between cities, but also to create lasting, tangible value for the communities it touches.

Importantly, a multi-modal pathway is complemented by bicycle-friendly trains and stations. People don't just travel between stations. They travel between origins and destinations. Bicycles help solve the "last-mile" problem and significantly increase the catchment area of rail stations. Cycling can also have a speed advantage over walking and driving, and reduces the need for large parking lots at stations and origin/destination parking.

Tourism is also supported by cycle-friendly trains and stations. Cycling day trips and long-distance "cycle one-way and return by train" trips become possible. This opens up new recreational opportunities and brings in tourism revenue for communities.

<div class="share-block">
  <h2>Share this page</h2>
  <p>If you found this useful, please share it with others.</p>

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
  <h2>Next step</h2>
  <p><a class="button button-primary" href="{{ '/issues-and-solutions/' | relative_url }}">Issues &amp; Solutions</a></p>
</div>
