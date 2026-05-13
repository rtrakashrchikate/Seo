# JSON-LD Schema Markup Package
## Advocate Akash Chikate | Pune Criminal Defence Lawyer

All 8 schemas below are production-ready. Copy each block and paste into the `<head>` section of the relevant page (or use a WordPress plugin like RankMath/Yoast to add via the custom schema field).

---

## Schema A: LegalService + Attorney (Homepage)

Place on: Homepage (`/`)

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": ["LegalService", "Attorney"],
  "@id": "https://advocateakashchikate.com/#legalservice",
  "name": "Advocate Akash Chikate — Criminal Defence Lawyer Pune",
  "alternateName": [
    "Akash Chikate Advocate",
    "Criminal Lawyer Pune",
    "Bail Lawyer Pune"
  ],
  "url": "https://advocateakashchikate.com/",
  "logo": "https://advocateakashchikate.com/wp-content/uploads/logo.png",
  "image": "https://advocateakashchikate.com/wp-content/uploads/akash-chikate-criminal-lawyer-pune.jpg",
  "description": "Advocate Akash Chikate is a criminal defence lawyer in Pune, Maharashtra, specialising in anticipatory bail (Section 482 BNSS), FIR quashing (Section 528 BNSS), NDPS defence, cyber crime law, POCSO, cheque bounce, domestic violence, and family criminal law. Practising at Pune District Court, Shivajinagar Court Complex, and the Bombay High Court with 8+ years of experience.",
  "telephone": "+91-XXXXX-XXXXX",
  "email": "contact@advocateakashchikate.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Office Address]",
    "addressLocality": "Shivajinagar",
    "addressRegion": "Maharashtra",
    "postalCode": "411005",
    "addressCountry": "IN"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": "18.5308",
    "longitude": "73.8474"
  },
  "areaServed": [
    {
      "@type": "City",
      "name": "Pune",
      "sameAs": "https://www.wikidata.org/wiki/Q1538"
    },
    {
      "@type": "City",
      "name": "Pimpri-Chinchwad"
    },
    {
      "@type": "City",
      "name": "Mumbai"
    },
    {
      "@type": "State",
      "name": "Maharashtra",
      "sameAs": "https://www.wikidata.org/wiki/Q1191"
    }
  ],
  "openingHoursSpecification": [
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday"],
      "opens": "10:00",
      "closes": "18:00"
    },
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": "Saturday",
      "opens": "10:00",
      "closes": "14:00"
    }
  ],
  "hasOfferCatalog": {
    "@type": "OfferCatalog",
    "name": "Criminal Law Practice Areas",
    "itemListElement": [
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "Anticipatory Bail — Section 482 BNSS 2023"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "Regular Bail — Section 480 BNSS 2023"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "FIR Quashing — Section 528 BNSS 2023"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "NDPS Act Defence"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "Cyber Crime Defence — IT Act 2000"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "POCSO Act Defence"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "Cheque Bounce — Section 138 NI Act"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "Domestic Violence Defence"}},
      {"@type": "Offer", "itemOffered": {"@type": "Service", "name": "Bombay High Court Bail Applications"}}
    ]
  },
  "memberOf": [
    {
      "@type": "Organization",
      "name": "Maharashtra and Goa Bar Council",
      "url": "https://www.maharashtrabarassociation.org/"
    },
    {
      "@type": "Organization",
      "name": "Bar Council of India"
    }
  ],
  "hasCredential": [
    {
      "@type": "EducationalOccupationalCredential",
      "credentialCategory": "degree",
      "name": "LL.M — Science & Technology Laws"
    },
    {
      "@type": "EducationalOccupationalCredential",
      "credentialCategory": "certificate",
      "name": "Diploma in Cyber Laws"
    }
  ],
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.9",
    "reviewCount": "47",
    "bestRating": "5",
    "worstRating": "1"
  },
  "sameAs": [
    "https://www.linkedin.com/in/akash-chikate/",
    "https://twitter.com/akashchikate"
  ],
  "priceRange": "Consultation available",
  "currenciesAccepted": "INR",
  "paymentAccepted": "Cash, Bank Transfer, UPI"
}
</script>
```

> **Note:** Replace `+91-XXXXX-XXXXX` with the actual phone number, `[Office Address]` with the street address, and update the `logo`, `image`, `sameAs` URLs to actual live URLs before deploying.

---

## Schema B: FAQPage (Anticipatory Bail Page)

Place on: `/anticipatory-bail-lawyer-pune/`

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is anticipatory bail under BNSS 2023?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Anticipatory bail under Section 482 of the Bharatiya Nagarik Suraksha Sanhita 2023 (BNSS 2023) is relief granted by a Sessions Court or High Court that protects a person from arrest. If the court grants anticipatory bail, the person is released on bail immediately upon any arrest. It replaced Section 438 of the CrPC. A key change under BNSS: the High Court must give 7 days' prior notice to the state government before hearing the application."
      }
    },
    {
      "@type": "Question",
      "name": "How long does anticipatory bail take in Pune?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "At Pune Sessions Court, anticipatory bail applications typically take 3 to 7 working days from filing to a hearing and order. At the Bombay High Court, the mandatory 7-day notice period to the state means the process takes approximately 14 to 21 days from filing. Urgent matters with compelling grounds can sometimes get a quicker listing."
      }
    },
    {
      "@type": "Question",
      "name": "What are the grounds for getting anticipatory bail?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Common grounds for anticipatory bail include: (1) no prima facie case against the applicant, (2) the underlying dispute is civil in nature, (3) no risk of the applicant absconding, (4) no risk of tampering with evidence, (5) cooperation with the investigation, (6) the FIR is mala fide or retaliatory, and (7) the applicant is a first-time offender with community roots."
      }
    },
    {
      "@type": "Question",
      "name": "Can anticipatory bail be granted in NDPS cases?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Anticipatory bail in NDPS commercial-quantity cases is significantly restricted by Section 37 of the NDPS Act, which imposes a twin-condition test. Courts must be satisfied that there are reasonable grounds to believe the accused is not guilty AND that the accused is unlikely to reoffend. For small-quantity NDPS matters, anticipatory bail is more accessible as Section 37 does not apply."
      }
    },
    {
      "@type": "Question",
      "name": "What documents are needed for anticipatory bail?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Key documents for an anticipatory bail application include: copy of the FIR (if available), identity proof (Aadhaar, PAN), proof of residence, employment or business proof (to show community ties), any documentary evidence showing the civil nature of the dispute (contracts, correspondence), and any prior court orders in related matters. Your advocate will prepare the application, grounds, and affidavit."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between anticipatory bail and regular bail?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Anticipatory bail (Section 482 BNSS) is obtained before arrest — it pre-empts custody entirely. Regular bail (Section 480 BNSS) is obtained after arrest — it secures release from custody. Anticipatory bail is generally more desirable as it prevents the trauma and stigma of arrest. Once arrested, regular bail must be sought, and the standard remains the same but the negotiating position is weaker."
      }
    },
    {
      "@type": "Question",
      "name": "Can anticipatory bail be cancelled?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Under Section 483(2) BNSS, anticipatory bail can be cancelled by the court that granted it, or by a superior court, if: the applicant violates bail conditions, tampers with evidence, threatens witnesses, commits another offence, or absconds. The prosecution must make a specific application for cancellation and show that the grounds for bail no longer subsist."
      }
    },
    {
      "@type": "Question",
      "name": "What is interim anticipatory bail?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Interim anticipatory bail is temporary protection granted by the court while the main anticipatory bail application is pending hearing. Under the BNSS 2023 proviso to Section 482(1), courts can grant interim anticipatory bail for a limited period to protect the applicant from arrest during the notice period or before the first hearing. It is typically valid for 7 to 14 days."
      }
    },
    {
      "@type": "Question",
      "name": "Which court handles anticipatory bail in Pune?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Anticipatory bail in Pune can be applied for at the Pune Sessions Court (located at Shivajinagar Court Complex) or the Bombay High Court. The Sessions Court is the first port of call for most matters. The Bombay High Court has jurisdiction when the Sessions Court has rejected the application or when the matter requires High Court intervention due to its gravity or complexity."
      }
    },
    {
      "@type": "Question",
      "name": "How much does anticipatory bail cost in Pune?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Advocate fees for anticipatory bail applications in Pune vary based on the complexity of the case, the offence involved, and the court (Sessions Court vs. Bombay High Court). Legal fees are discussed privately in consultation. Bar Council of India rules prohibit public disclosure of fee structures. Contact Advocate Akash Chikate for a consultation."
      }
    }
  ]
}
</script>
```

---

## Schema C: Article (Anticipatory Bail Guide)

Place on: `/anticipatory-bail-guide/` or any blog article about anticipatory bail

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Article",
  "@id": "https://advocateakashchikate.com/anticipatory-bail-guide/#article",
  "headline": "Anticipatory Bail Under Section 482 BNSS 2023: Complete Guide for Pune",
  "description": "A comprehensive guide to anticipatory bail under Section 482 BNSS 2023, covering eligibility, grounds, procedure at Pune Sessions Court and Bombay High Court, key changes from CrPC Section 438, and how to protect yourself before arrest.",
  "image": "https://advocateakashchikate.com/wp-content/uploads/anticipatory-bail-guide-pune.jpg",
  "author": {
    "@type": "Person",
    "@id": "https://advocateakashchikate.com/#person",
    "name": "Advocate Akash Chikate",
    "jobTitle": "Criminal Defence Lawyer",
    "worksFor": {
      "@id": "https://advocateakashchikate.com/#legalservice"
    }
  },
  "publisher": {
    "@type": "Organization",
    "@id": "https://advocateakashchikate.com/#organization",
    "name": "Advocate Akash Chikate",
    "logo": {
      "@type": "ImageObject",
      "url": "https://advocateakashchikate.com/wp-content/uploads/logo.png"
    }
  },
  "datePublished": "2025-01-15",
  "dateModified": "2026-05-01",
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://advocateakashchikate.com/anticipatory-bail-guide/"
  },
  "keywords": "anticipatory bail, Section 482 BNSS, bail before arrest, Pune bail lawyer, anticipatory bail Pune, BNSS 2023 bail",
  "articleSection": "Criminal Law",
  "about": [
    {
      "@type": "LegalDocument",
      "name": "Bharatiya Nagarik Suraksha Sanhita 2023",
      "legislationIdentifier": "Section 482 BNSS"
    }
  ],
  "citation": [
    {
      "@type": "LegalDocument",
      "name": "Bharatiya Nagarik Suraksha Sanhita 2023, Section 482"
    },
    {
      "@type": "LegalDocument",
      "name": "Code of Criminal Procedure 1973, Section 438 (repealed)"
    }
  ]
}
</script>
```

---

## Schema D: BreadcrumbList (Service Pages & Guides)

### D1 — For /anticipatory-bail-lawyer-pune/

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://advocateakashchikate.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Practice Areas",
      "item": "https://advocateakashchikate.com/practice-areas/"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "Anticipatory Bail Lawyer Pune",
      "item": "https://advocateakashchikate.com/anticipatory-bail-lawyer-pune/"
    }
  ]
}
</script>
```

### D2 — For /anticipatory-bail-guide/ (blog/resource)

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://advocateakashchikate.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Resources",
      "item": "https://advocateakashchikate.com/resources/"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "Anticipatory Bail Guide",
      "item": "https://advocateakashchikate.com/anticipatory-bail-guide/"
    }
  ]
}
</script>
```

---

## Schema E: LocalBusiness (Shivajinagar Office)

Place on: Homepage (add to existing `<head>` or merge with LegalService schema)

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "@id": "https://advocateakashchikate.com/#localbusiness",
  "name": "Advocate Akash Chikate — Criminal Lawyer Pune",
  "image": "https://advocateakashchikate.com/wp-content/uploads/office-shivajinagar-pune.jpg",
  "telephone": "+91-XXXXX-XXXXX",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Office Address]",
    "addressLocality": "Shivajinagar",
    "addressRegion": "Maharashtra",
    "postalCode": "411005",
    "addressCountry": "IN"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 18.5308,
    "longitude": 73.8474
  },
  "url": "https://advocateakashchikate.com/",
  "openingHoursSpecification": [
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday"],
      "opens": "10:00",
      "closes": "18:00"
    },
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": "Saturday",
      "opens": "10:00",
      "closes": "14:00"
    }
  ],
  "hasMap": "https://maps.google.com/?q=Shivajinagar+Court+Complex+Pune",
  "priceRange": "Consultation available",
  "servesCuisine": null,
  "sameAs": [
    "https://www.google.com/maps?cid=YOUR_GBP_CID",
    "https://www.linkedin.com/in/akash-chikate/"
  ]
}
</script>
```

> Replace `YOUR_GBP_CID` with the Google Business Profile CID found in the GBP dashboard URL.

---

## Schema F: Person / Author (Advocate Akash Chikate)

Place on: Homepage and About page

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "@id": "https://advocateakashchikate.com/#person",
  "name": "Akash Chikate",
  "alternateName": "Advocate Akash Chikate",
  "givenName": "Akash",
  "familyName": "Chikate",
  "jobTitle": "Criminal Defence Lawyer",
  "description": "Advocate Akash Chikate is a criminal defence lawyer practising at Pune District Court, Shivajinagar Court Complex, and the Bombay High Court. He holds an LL.M in Science & Technology Laws and a Diploma in Cyber Laws, with 8+ years of criminal law experience and 27+ Bombay High Court orders.",
  "url": "https://advocateakashchikate.com/about/",
  "image": "https://advocateakashchikate.com/wp-content/uploads/akash-chikate-criminal-lawyer-pune.jpg",
  "alumniOf": [
    {
      "@type": "EducationalOrganization",
      "name": "[Law School / University Name]"
    }
  ],
  "hasCredential": [
    {
      "@type": "EducationalOccupationalCredential",
      "credentialCategory": "degree",
      "name": "Bachelor of Laws (LL.B)"
    },
    {
      "@type": "EducationalOccupationalCredential",
      "credentialCategory": "degree",
      "name": "Master of Laws (LL.M) — Science & Technology Laws"
    },
    {
      "@type": "EducationalOccupationalCredential",
      "credentialCategory": "certificate",
      "name": "Diploma in Cyber Laws"
    },
    {
      "@type": "EducationalOccupationalCredential",
      "credentialCategory": "license",
      "name": "Maharashtra and Goa Bar Council Enrollment",
      "recognizedBy": {
        "@type": "Organization",
        "name": "Bar Council of India"
      }
    }
  ],
  "knowsAbout": [
    "Anticipatory Bail",
    "Regular Bail",
    "FIR Quashing",
    "NDPS Act Defence",
    "Cyber Crime Law",
    "POCSO Act",
    "Cheque Bounce NI Act 138",
    "Domestic Violence Law",
    "BNSS 2023",
    "BNS 2023",
    "BPSS 2023",
    "Bombay High Court Practice",
    "Criminal Law Maharashtra"
  ],
  "worksFor": {
    "@type": "LegalService",
    "@id": "https://advocateakashchikate.com/#legalservice",
    "name": "Advocate Akash Chikate — Criminal Defence Lawyer Pune"
  },
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Shivajinagar",
    "addressRegion": "Maharashtra",
    "postalCode": "411005",
    "addressCountry": "IN"
  },
  "sameAs": [
    "https://www.linkedin.com/in/akash-chikate/",
    "https://twitter.com/akashchikate"
  ]
}
</script>
```

---

## Schema G: WebSite with SearchAction

Place on: Homepage only

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "@id": "https://advocateakashchikate.com/#website",
  "url": "https://advocateakashchikate.com/",
  "name": "Advocate Akash Chikate | Criminal Lawyer Pune",
  "description": "Official website of Advocate Akash Chikate, criminal defence lawyer in Pune, Maharashtra. Specialising in anticipatory bail, FIR quashing, NDPS, cyber crime, POCSO, and Bombay High Court matters.",
  "publisher": {
    "@id": "https://advocateakashchikate.com/#organization"
  },
  "inLanguage": ["en-IN", "mr"],
  "potentialAction": {
    "@type": "SearchAction",
    "target": {
      "@type": "EntryPoint",
      "urlTemplate": "https://advocateakashchikate.com/?s={search_term_string}"
    },
    "query-input": "required name=search_term_string"
  }
}
</script>
```

---

## Schema H: Organization

Place on: Homepage (alongside LegalService schema)

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "@id": "https://advocateakashchikate.com/#organization",
  "name": "Advocate Akash Chikate — Criminal Law Practice",
  "alternateName": "Akash Chikate Advocate",
  "url": "https://advocateakashchikate.com/",
  "logo": {
    "@type": "ImageObject",
    "url": "https://advocateakashchikate.com/wp-content/uploads/logo.png",
    "width": 300,
    "height": 60
  },
  "image": "https://advocateakashchikate.com/wp-content/uploads/akash-chikate-criminal-lawyer-pune.jpg",
  "description": "Criminal defence law practice in Pune, Maharashtra, led by Advocate Akash Chikate. Specialising in bail applications, FIR quashing, NDPS defence, cyber crime law, and Bombay High Court matters.",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Office Address]",
    "addressLocality": "Shivajinagar",
    "addressRegion": "Maharashtra",
    "postalCode": "411005",
    "addressCountry": "IN"
  },
  "telephone": "+91-XXXXX-XXXXX",
  "email": "contact@advocateakashchikate.com",
  "foundingDate": "2016",
  "founder": {
    "@id": "https://advocateakashchikate.com/#person"
  },
  "member": [
    {
      "@id": "https://advocateakashchikate.com/#person"
    }
  ],
  "sameAs": [
    "https://www.linkedin.com/in/akash-chikate/",
    "https://twitter.com/akashchikate",
    "https://www.google.com/maps?cid=YOUR_GBP_CID"
  ]
}
</script>
```

---

## Deployment Checklist

- [ ] Schema A (LegalService): Added to homepage `<head>`
- [ ] Schema B (FAQPage): Added to anticipatory bail page
- [ ] Schema C (Article): Added to each blog post/guide
- [ ] Schema D1 (Breadcrumb): Added to each service page
- [ ] Schema D2 (Breadcrumb): Added to each resource/guide page
- [ ] Schema E (LocalBusiness): Added to homepage
- [ ] Schema F (Person): Added to homepage and About page
- [ ] Schema G (WebSite/SearchAction): Added to homepage
- [ ] Schema H (Organization): Added to homepage
- [ ] All placeholder values replaced (phone, address, image URLs, GBP CID)
- [ ] Validated at: https://search.google.com/test/rich-results
- [ ] Validated at: https://validator.schema.org/
- [ ] No errors in Google Search Console > Enhancements

> Create additional FAQPage schemas for NDPS, FIR quashing, cyber crime, and POCSO pages using the same pattern as Schema B — 10 Q&As per page.
