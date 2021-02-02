---
title: Supporters
layout:  null
altfooter: true
tab: true
order: 7
tags: juiceshop
---

## Project Supporters

> You can attribute your donation to the OWASP Juice Shop project by
> using
> [this link](/donate?reponame=www-project-juice-shop&title=OWASP+Juice+Shop)<!-- @IGNORE PREVIOUS: link -->
> or the green "Donate"-button while on any tab of the Juice Shop
> project page!

### Top Supporters

[![Wild West Hackin' Fest](assets/images/wwhf_header.png)](https://wildwesthackinfest.com/)

<small><small>_In order to be recognized as a "Top Supporter" a company
must have donated $1000 or more a) to OWASP while attributing it to
Juice Shop or b) as a restricted gift to OWASP Juice Shop in the last 12
months._</small></small>

#### All Corporate Supporters

* [RandoriSec](https://randorisec.fr/)<sup>(2021)</sup>
* [Wild West Hackin' Fest](https://wildwesthackinfest.com/)<sup>(2020)</sup>
  <!-- >=1000€ @ 03.08.2020 -->
* [Denim Group](http://www.denimgroup.com/)<sup>(2018-2019)</sup> <!--
  \>=1000€ @ 26.08.2018 & 20.09.2019 -->
* [secuvera](https://www.secuvera.de/)<sup>(2018-2019)</sup>
* [New Work SE](https://www.new-work.se/en/about-new-work-se)<sup>(2019)</sup>
  <!-- >=1000€ @ 19.12.2019 -->
* [PlexTrac](https://plextrac.com)<sup>(2019)</sup>
* [Silpion](https://silpion.de)<sup>(2019)</sup>
* [iteratec](https://www.iteratec.de/)<sup>(2017)</sup> <!-- >=1000€ @
  30.11.2017 -->
* [eSailors](https://www.esailors.de/)<sup>(2016)</sup> <!-- >=1000€ @
  31.07.2017 -->
* [XING](https://corporate.xing.com/en/about-xing/security/)<sup>(2016)</sup>

  <!-- >=1000€ @ 26.09.2016 -->

#### All Individual Supporters

{% assign individual_supporter = site.data.ow_attributions | uniq %}
{% for supporter in individual_supporter %}
* {{ supporter | strip_html | strip_newlines | strip }}
{% endfor %}
* _You want to appear on this list?_
  [Donate to OWASP here! 🤲](/donate?reponame=www-project-juice-shop&title=OWASP+Juice+Shop)<!-- @IGNORE PREVIOUS: link -->

#### All Corporate-sponsored Code Contributions

* [#1221](https://github.com/bkimminich/juice-shop/pull/1221),
  [#1356](https://github.com/bkimminich/juice-shop/pull/1356):
  [Panasonic Information Systems Company Europe](https://application.job.panasonic.eu/data/ruP0pHQvHrGZJKvL/rc.php?nav=jobsearch&custval12=ite&lang=EN&custval11=PBSEU_GER)<sup>(2019-2020)</sup>

<small><small>_In order to be recognized as a "Corporate-sponsored Code
Contribution" an offical written confirmation of waiving all IP to the
contributed code must be formally submitted to the OWASP
Foundation._</small></small>

#### LeanPub Royalties

[![Pwning OWASP Juice Shop](https://raw.githubusercontent.com/bkimminich/pwning-juice-shop/master/cover_small.jpg)](https://leanpub.com/juice-shop)

$1,251.68 of royalties from
[Björn Kimminich](https://kimminich.de)'s eBook have been donated to the
project between 09/2017 and 07/2019.

---

_The OWASP Foundation is very grateful for the support by the
individuals and organizations listed. However please note, the OWASP
Foundation is strictly vendor neutral and does not endorse any of its
supporters._
