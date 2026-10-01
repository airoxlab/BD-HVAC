# BD HVAC

Single-page website for BD HVAC — a licensed C-20 HVAC contractor in Milpitas, California,
serving the South Bay.

- **Owner:** not published (unknown — "BD" appears to be initials; ask him and add an about line)
- **Phone:** (408) 705-5551
- **Location:** Milpitas, CA (home-based — street address deliberately not published)
- **CSLB license:** #1147295, C-20 Warm-Air Heating/Ventilating/Air-Conditioning, licensed Dec 2025
- **Status:** $25,000 bond, insured with workers' compensation (has employees)
- **Service area:** Milpitas, San Jose, Fremont, Santa Clara, Sunnyvale, South Bay

Services: heat pumps, ductless mini-splits, AC installation and replacement, AC repair,
furnace and heating repair, maintenance and tune-ups, ductwork.

## Structure

- `index.html` — the complete site (self-contained CSS, no build step)
- `img/` — 8 verified stock HVAC photographs, credited in the footer
- `favicon.svg` — BD monogram on the brand green

Eight sections: hero, services, heat pump feature, why us, licensed/bonded/insured, areas served,
FAQ, contact. Mobile-first, dark-mode aware.

## Positioning

Per the brief, this leads on **heat pumps and efficiency** rather than emergency AC — the right
angle for the Bay Area, where the climate is mild on both ends and homeowners respond to
efficiency messaging. The dedicated heat pump section explains why the South Bay climate suits
them, and mini-splits are positioned for ADUs, additions and older homes without ductwork, which
is a common South Bay situation.

The short name is carried as a bold **BD monogram** in the header, footer and favicon.

## SEO

- **HVACBusiness + LocalBusiness schema** with areaServed for all five cities plus South Bay,
  the CSLB credential, and knowsAbout covering heat pumps and mini-splits.
- **FAQPage schema** with six real Q&As, eligible for FAQ rich results.
- Open Graph and geo meta tags; title and description target "heat pump Milpitas",
  "HVAC San Jose" and related terms.

## Sourcing notes

First website — no prior web presence, no Google/Facebook/Yelp/Instagram. No reviews, ratings or
follower counts exist, and none appear on the site.

**Address is deliberately not published.** 532 Walnut Dr is the owner's home. The site shows
"Milpitas, CA" and the service area only — which is also what Google recommends for service-area
businesses. Verified: the string "Walnut" appears nowhere in the HTML.

**Owner name is omitted** because it was not supplied. Worth asking — an "about the owner" line
adds real credibility to a business licensed in December 2025 with nothing else online.

**Rebates are mentioned without numbers.** Heat pump incentives change frequently and vary by
utility, so the site says to ask and to confirm with the utility directly rather than quoting a
figure that could be wrong by the time someone reads it.

All 8 photos are verified stock, disclosed in the footer as representative rather than completed
jobs. Rejected during sourcing: a CGI-rendered interior, a paper mill, and a derelict basement.

Open `index.html` in a browser, or deploy the folder as-is to any static host.
