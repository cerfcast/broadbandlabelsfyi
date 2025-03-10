---
layout: home
---

As well-trained grocery shoppers in the United States, we are all familiar with _that_ flip of the wrist -- the one that manipulates the peanut butter jar, the box of cereal or the head of lettuce in a way that exposes the nutrition label. While there is always room for improvement, we rely on the information in the nutrition labels to seek out the foods that contain the ingredients we want and avoid the ones that would cause us an allergic reaction, interfere with our medicine, etc.

In the same way that the information on nutrition labels is part of what makes an efficient market where consumers can make informed choices on what to buy and eat and producers can transparently describe what makes their food so tasty, "nutrition labels" on broadband providers "helps consumers make informed choices and is central to a well-functioning marketplace that encourages competition, innovation, low prices, and high-quality service."[^fcc1]

[^fcc1]: “Broadband Consumer Labels.” 2022. Federal Communications Commission. February 23, 2022. https://www.fcc.gov/broadbandlabels.

After more than 15 years of advocacy,[^over] the vision of [Sascha Meinrath](https://www.bellisario.psu.edu/people/individual/sascha-meinrath), who originally championed the idea of broadband nutrition labels with his colleagues at [New America](https://www.newamerica.org/), has become reality. 

[^over]: "Faculty Member’s Wait for Broadband Labels Finally Ends." 2024. Psu.edu. 2024. https://communicator.bellisario.psu.edu/article/faculty-members-wait-for-broadband-labels-finally-ends.

## They _Were_ Hard To Find

Unlike nutrition labels on food, the required[^required] broadband nutrition labels are, well, a little bit hard to find.[^wsj]

[^required]: FCC.

[^wsj]: Patience Haggin. "Internet Plans Now Come With ‘Nutrition Labels.’ No One Knows How to Read Them," _Wall Street Journal_, December 8, 2024. [https://www.wsj.com/business/telecom/internet-broadband-plan-labels-793cc460](https://www.wsj.com/business/telecom/internet-broadband-plan-labels-793cc460).

Or, should we say, _were_ hard to find! With _your_ help, the nutrition labels are now easy to find. Just look at the list below to locate your ISP and use the link to go directly to the page containing the nutrition labels!

### Want To Help?

Know an ISP that should be on the list? We would _love_ your contribution. Check out our [`README.md`](https://github.com/cerfcast/broadbandlabelsfyi/) for information on how to contribute!

## Broadband Label URLs:

| Provider | Nutrition Label |
| --- | --- |
{%- for info in site.data.locations %}
| [{{ info.provider }}]({{ info.purl }}) | [Link]({{ info.blurl }}) |
{%- endfor -%}
