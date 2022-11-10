---
label: Demos
description: The Demos track at CUI !!conference.year!! allows authors to present interactive contributions aiming to tackle challenges and show progress in the field of conversational user interfaces.

splash_title: Demos<br>at CUI !!conference.year!!

cta:
  text: Submissions not open yet
  title: Submissions for the demos track is currently closed
#  link: /2023/submit/pcs/
  
track:
  chairs: postersdemos
  dates: demos

menus:
  submit:
    title: Demos
    alt: Information about submitting to the demos track at CUI !!conference.year!!
    weight: 3
    is_track: true

lastmod: page
---

# Demo submission information

Demos are interactive contributions aiming to tackle challenges and show progress in the field of Conversational User Interfaces.  
 
For the submission and review process, you should write an extended abstract that summarises your demo. If accepted, we will invite you to present your work at CUI 2023, with your extended abstract published in the conference proceedings. 

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## Examples of demos at CUI

Some examples of previously successful submissions can be found below: 

* [ALTCAI: Enabling the Use of Embodied Conversational Agents to Deliver Informal Health Advice during Wizard of Oz Studies](https://dl.acm.org/doi/abs/10.1145/3469595.3469621 "Read 'ALTCAI: Enabling the Use of Embodied Conversational Agents to Deliver Informal Health Advice during Wizard of Oz Studies' on ACM Digital Library")
* [How can AI leverage alternative criteria and suggest a better way to measure credit worthiness and economic growth?](https://dl.acm.org/doi/abs/10.1145/3543829.3544537 "Read 'How can AI leverage alternative criteria and suggest a better way to measure credit worthiness and economic growth?' on the ACM Digital Library")
* [Perceived Usefulness of Conversational Agents Predicts Search Performance in Aerospace Domain](https://dl.acm.org/doi/abs/10.1145/3405755.3406172 "Read 'Perceived Usefulness of Conversational Agents Predicts Search Performance in Aerospace Domain' on the ACM Digital Library")


## The process

All demo papers will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.


### 1. Prepare your manuscript and video

Submissions of extended abstracts for demos must be in English, in PDF format, anonymised using the [CHI anonymization policy](https://chi2022.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "CHI 2022 Anonymization Policy"), and approximately 3,000 words (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments).

You should include a description of the system, a description of the problem(s) it addresses, a discussion regarding its novelty and/or applied context, a discussion regarding the technology’s relevance to the CUI community, a description of the planned presentation, and details about how online attendees will interact with the demonstration. Your description of the planned presentation should focus on how you will provide an engaging interactive experience for your audience.

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates for Microsoft Word and LaTeX") to prepare your submission.  LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"), which we strongly encourage. LaTeX users should have the following document class: <code>\documentclass[sigconf, screen, review, anonymous]{acmart}</code> for submission.

Word users should use [the double-column "Interim Template"](https://www.acm.org/publications/proceedings-template#h-interim-template "ACM Interim Template for submissions") during submission and review and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline. Word users may be required to reimplement their paper, if accepted, into the correct document format for the publishing process.

ACM's CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.

You should also prepare a 2 minute (max) video demonstration of your demo.

### 2. Submit your manuscript and video

You should submit your extended abstract and video to the [conference submission system]({{ "/submit/pcs/" | relative_url }} "CUI {{ site.conference.year }} submission system"). You must include your title, abstract, author details, and paper as a PDF, and your short video. Your paper and video must be anonymised, or it may be desk rejected. 

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission").

### 3. Await reviews

Each submission will be reviewed by one track chair and one expert reviewer through a curated process. Following a curated selection process, successful submissions will be invited to present at CUI {{ site.conference.year }}.In curating the program creativity in delivery, feasibility, novelty, and ability to engage attendees in-person and online will be assessed. Our aim is to deliver an array of captivating demonstrations that showcase the diverse research arenas contributing to the conversational user interface research community. Sensitive, private and/or proprietary information should not be disclosed prior to publication. Business exposure is reserved for event sponsors only, so advertising materials should not be used in demonstrations. 

### 4. Prepare your manuscript for publication

If your demo is accepted, you should de-anonymise it. You must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

At least one author of each accepted demo must register for the conference, otherwise we cannot guarantee publication of your paper. Accepted demo extended abstract will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>.

You will receive an email from ACM to assign the rights for your paper, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your paper. Accepted papers will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM's guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

### 5. Present your work

Authors be given the opportunity to present their demo during a dedicated session. The specific details of this presentation will be provided closer to the conference.



## Questions?

<p>
{%- for group in site.data.oc -%}
{%- for role in group[1]['roles'] -%}
{%- if role[0] == page.track.chairs -%}
  If you have any questions, please contact the <a href="{{ role[1].email }}" title="Send an email to the CUI {{ site.conference.year }} {{ role[1].label }}">{{ role[1].label }}</a>, 
  {% assign use_and = role[1]['people'] | size | plus: -1 -%}
  {%- for person in role[1]['people'] -%}
      {{- person.name -}}
      {%- if forloop.index == use_and %} and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%}
  {%- endfor %} for support.
  {%- break -%}
{%- endif -%}
{%- endfor -%}
{%- endfor -%}
</p>