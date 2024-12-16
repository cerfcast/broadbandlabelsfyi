---
layout: home
---

## Broadband Labels _Were_ Hard To Find

As well-trained grocery shoppers in the United States, we are all familiar with _that_ flip of the wrist -- the one that manipulates the peanut butter jar, the box of cereal or , the head of lettuce in a way that exposes the nutrition label. While there is always room for improvement, we rely on the information in the nutrition labels to seek out the foods that contain the nutrition we want and avoid the ones that would cause us an allergic reaction, interfere with our medicine. etc.

In the same way that the information on nutrition labels is part of what makes an efficient market where consumers can make informed choices on what to buy and eat and producers can transparently describe what makes their food so tasty, "nutrition labels" on broadband providers "helps consumers make informed choices and is central to a well-functioning marketplace that encourages competition, innovation, low prices, and high-quality service."[^fcc1]

[^fcc1]: “Broadband Consumer Labels.” 2022. Federal Communications Commission. February 23, 2022. https://www.fcc.gov/broadbandlabels.

After more than 15 years of advocacy, the vision of Sascha Meinrath, who originally championed the idea of broadband nutrition labels with this colleagues at the New America Foundation, has become reality. 

## Broadband Label URLs:

| Provider | Label URL |
| --- | --- |
{%- for info in site.data.locations %}
| {{ info.provider }} | {{ info.link }} |
{%- endfor -%}
