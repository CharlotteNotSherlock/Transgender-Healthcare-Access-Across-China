# Transgender-Healthcare-Access-Across-China
Methodology:
1.Data Collection & Sources:
The project, using verified hospital portals, and community-maintained resource sheets, identified and cataloged clinics and practitioners offering gender-affirming care across China, with all records updated through July 2026. Where official hospital channels were insufficient, listings were cross-checked against active community archives to confirm their accuracy. In order to ensure community-recommended practices were aligned with doctor-level practice, I consulted with publicly available registry data and talked to doctors individually to confirm.

2.Variables & Criteria:
A provider was classified as "transgender-friendly" if it met three criteria: documented clinical experience treating transgender patients, an absence of reported microaggressions or offensive conduct amongst community members and community reports, and the legal authorization (typically Tier-3/Class 3A hospitals) to prescribe Gender-Affirming Hormone Therapy.

Medication status was sorted into a three-tier framework: "Yes" (officially approved by the National Medical Products Administration), "Not Available" (explicitly banned or never approved), and "N/A" (Medications that have never been formally approved or used for transgender gender-affirming hormone therapy in clinical practice in China). The analysis anchored its evaluation of online prescriptions strictly on regulatory compliance with NMPA standards, rather than unofficial digital channels, reflecting the government's tightened oversight of remote hormone therapy dispensing.

3.Geocoding & Technical Pipeline:
Hospital addresses were converted into precise latitude and longitude coordinates using the Amap application programming interface. Those coordinates were then rendered onto a custom web map using Mapbox GL JS; the project’s Mapbox API token functioned as the authentication gateway, allowing Mapbox's servers to generate the underlying base map and plot markers at each corresponding geographic location. A manual verification pass was conducted to confirm that no records were missing from the final mapping set.

4.Ethics & Privacy:
To protect patient and medical practitioner privacy, all individual identities and non-public personal information were excluded from the dataset. The project is intended solely as a data visualization of medical resource availability across China and is not a substitute for professional medical guidance or an official clinical manual.

5.Limitations:
The analysis acknowledges that practitioner availability remains highly dynamic and heavily reliant on individual doctor discretion, making long-term real-time verification challenging. The dataset reflects inherently higher visibility in major urban centers due to stronger community feedback networks in those regions. The project deliberately excludes unregulated black-market or gray-market supply chains, or any informal healthcare navigation tactics used in less-resourced areas, confining its scope exclusively to formal, visible, and legally sanctioned medical avenues.
