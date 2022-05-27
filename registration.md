---
layout: page
title: Registration
registration_state: notyet
email: gapdays2022-summer@gapdays.de
---

{% case page.registration_state %}
{% when 'notyet' %}
<p class="message">Registration will be open soon.</p>

{% when 'closed' %}
<p class="message">Registration is closed.</p>

{% when 'open' %}
<p class="message">Registration is open.</p>

In order to participate in this meeting, please register with us, even if you only want to join for parts of the meeting.

To register please send an email to [{{site.email}}](mailto:{{site.email}}) with the following contents.
```
Registration for {{site.title}}

Name: ...
Email: ...
Affiliation: ... (Please enter the name of your home university, institute etc., if any. )
Arrival date: ... (Please enter the day of arrival. We will start Monday, October 17, 10 am.)
Departure date: ... (Please enter the day of departure. We will finish Friday, October 21, afternoon.)
Accommodation: Yes/No (Please indicate whether you would like us to book a room at the RWTH Guesthouse for you.)
Reimbursements: ... (Expenses for travel and accommodations might be partly covered. Please give us an estimation how much support you will need.)
Mensa Card: Yes/No (Please indicate if you wish to have lunch at the university canteen. See <a href="{{ site.url }}{{ site.baseurl
    }}/location">here.)
Child Care: Yes/No (Please indicate if child care is needed. We will contact you individually for further details.)
Presentation: ... (If you like to give a presentation during the package session please state the title of your presentation.
You are welcome to offer other talks, too.)
Comments: ... (Here you can give any comments, questions, or wishes that you have regarding the GAP Days.)
```

<p>
If you have any questions
regarding registration, or in general, feel free to
<a href="mailto:{{site.email}}">contact us via email</a>.
</p>
{% endcase %}
