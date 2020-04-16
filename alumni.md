---
layout: page
title: Reconnecting with other Alumni
permalink: /get-involved/alumni
---

# Alumni Board
While the Alumni Board is comprised of specific positions, we encourage any and everyone to be active within the alumni group. Even if you can only spare a few minutes of your time, we could always use it! Please contact [Jerry Tozer](mailto:jltozer@mtu.edu) to get on our Alumni Executive Board email list.

{% include spotlight-inline.html
  name="Alex Ott"
  init-year="11"
  position="Alumni President"
  email_address="ajott@mtu.edu"
  cover-image="/assets/img/people/ott.png"
content="Alex served the Active Chapter in a number of positions, including VP of Member Development. He spent one year as the Active Advisor to the National Council. He currently lives and works in Grand Rapids, MI"%}

{% include spotlight-inline.html
  name="Darien Benner"
  init-year="15"
  position="Alumni Treasurer"
  email_address="dtbenner@mtu.edu"
  cover-image="/assets/img/people/darien.png"
  content="Darien served the Active Chapter as President, and has remained involved as an alumnus. He currently lives and works in the Detroit area"%}

{% include spotlight-inline.html
  name="Jerry Tozer"
  init-year="13"
  position="Alumni Secretary"
  email_address="jltozer@mtu.edu"
  cover-image="/assets/img/people/jerry.png"
  content="Jerry served the Active Chapter as Secretary and as the Active President. He currently lives and works in Muskegon, MI"%}

# Committees

Committees are established to better serve the Alumni and Active Organizations. Generally, these committees include those for the Chapter House and the quinquennial Alumni Reunion. If you are interested in getting involved in a committee, send an email to the [Alumni Board](mailto:alumeboard-triangle-l@mtu.edu).



{% for file in site.static_files %}
{% if file.path contains "/assets/docs/newsletters/" %}
- [{{ file.basename }}]({{ file.path | relative_url }})
{% endif %}
{% endfor %}

# Donations

Donations are used for:
- Chapter financial support during COVID19 crisis
- Reimbursement of Pledge Fees for Dean's List achievers
- Equipment for Winter Carnival
- Travel assistances for National events
- Alumni National Chapter Fee

<!-- Donation cards -->
<div class="row">
<div class="col-lg-6 mb-6">
{% include paypal-card.html paypal-id="VDS37JZR7LQAQ" header="One-Time Donation" content="
Contribute to Triangle Fraternity Alumni with a one-time donation.
"%}
</div>
<div class="col-lg-6 mb-6">
{% include paypal-card.html paypal-id="D2BA3SJRMPVSS" header="Monthly Donation Club" content='
<input type="hidden" name="on0" value="Support our organization. Join a donation club!">
<select name="os0">
    <option value="Mr. T">Mr. T : $100.00 USD - monthly</option>
    <option value="Mr. Bigshot">Mr. Bigshot : $75.00 USD - monthly</option>
    <option value="Half Way There">Half Way There : $50.00 USD - monthly</option>
    <option value="I\'ll Share The Wealth">I\'ll Share The Wealth : $30.00 USD - monthly</option>
    <option value="Wilmer\'s Club">Wilmer\'s Club : $20.00 USD - monthly</option>
    <option value="I\'m giving her all she\'s got!">I\'m giving her all she\'s got! : $10.00 USD - monthly</option>
    <option value="I still got loans man!">I still got loans man! : $5.00 USD - monthly</option>
</select>
'%}
</div>
</div>
