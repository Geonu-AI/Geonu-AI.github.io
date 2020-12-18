---
title: "Regression Analysis of SiNx Intrinsic Film Stress"

---

{% capture fig_img %}
![Foo]({{ '/assets/images/NN_Prediction.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Prediction of neural network trained over 10,000 epochs.</figcaption>
</figure>


{% capture fig_img %}
![Foo]({{ '/assets/images/NN_changes_over_epochs.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>NN prediction changes over epochs.</figcaption>
</figure>

{% capture fig_img %}
![Foo]({{ '/assets/images/NN_Cost_over_epochs.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>NN cost changes over epochs.</figcaption>
</figure>

{% capture fig_img %}
![Foo]({{ '/assets/images/Linear_Regression_Y_versus_Y_predicted_with_DevSet.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Linear regression analysis.</figcaption>
</figure>

{% capture fig_img %}
![Foo]({{ '/assets/images/Linear_Regression_Cost_versus_Epoch.png' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Linear regression cost changes over epochs.</figcaption>
</figure>

