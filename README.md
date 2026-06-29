# Web Security Community Toolkit

A community-driven initiative for hosting web security workshops and meetups, adapting patient data privacy compliance practices from clinical research to strengthen our collective security posture.

---

## 🎯 Mission

Connect web security practitioners, researchers, and enthusiasts in Portland to share knowledge, practice defensive techniques, and build a stronger security community — informed by the rigorous privacy standards used in clinical research.

---

## 🏥 Clinical Trial Privacy Insights (Adapted for Web Security)

Clinical trials operate under some of the strictest data privacy frameworks in existence. Here are key compliance practices we can adapt for web security community operations:

### 1. **De-identification & Data Minimization**
- **Clinical Practice:** Patient data is de-identified before analysis; only the minimum necessary data is collected (HIPAA Safe Harbor & Expert Determination methods).
- **Web Security Adaptation:** When running security workshops, anonymize participant data in datasets, use synthetic data for demos, and apply data minimization principles to any telemetry or tracking.

### 2. **Informed Consent with Transparency**
- **Clinical Practice:** Participants must be fully informed about how their data will be collected, used, stored, and shared — with clear, jargon-free consent forms.
- **Web Security Adaptation:** Apply the same transparency to community members: clearly communicate what data is collected during events (e.g., photos, attendance lists, network capture data), how it's used, and who has access.

### 3. **Role-Based Access Control (RBAC)**
- **Clinical Practice:** Access to patient data is restricted based on role (investigator, coordinator, auditor) with the principle of least privilege enforced rigorously.
- **Web Security Adaptation:** Implement RBAC for community tools — workshop organizers, speakers, and attendees should each have appropriate access levels. Admin privileges should be limited and audited.

### 4. **Encryption at Rest & In Transit**
- **Clinical Practice:** All patient data must be encrypted both at rest (AES-256) and in transit (TLS 1.2+), with key management protocols in place.
- **Web Security Adaptation:** Ensure all community communications (email lists, chat platforms, file shares, event registrations) use end-to-end encryption or TLS. Encrypt stored sensitive data like attendance records and contact lists.

### 5. **Audit Logging & Accountability**
- **Clinical Practice:** Every access to patient data is logged with who, what, when, and why — enabling full traceability and accountability.
- **Web Security Adaptation:** Maintain audit logs of all administrative actions on community platforms, repository access, and data handling. Make logs available for review by trusted community members.

### 6. **Data Retention & Disposal Policies**
- **Clinical Practice:** Data is retained only as long as necessary for the study, then securely destroyed with documented disposal methods.
- **Web Security Adaptation:** Define clear data retention schedules for event materials, attendee lists, and workshop recordings. Automatically purge data that's no longer needed and document disposal.

### 7. **Third-Party Vendor Assessment**
- **Clinical Practice:** Any third-party service handling patient data must undergo rigorous security assessment (including BAAs, SOC 2, etc.).
- **Web Security Adaptation:** Before adopting any community tool (mailing platforms, video conferencing, file storage), assess their security posture, privacy policies, and data handling practices.

### 8. **Incident Response & Breach Notification**
- **Clinical Practice:** HIPAA requires breach notification within 60 days; clinical sites maintain incident response plans specifically for data breaches.
- **Web Security Adaptation:** Have a clear incident response plan for community platforms — define what constitutes a security incident, notification timelines, and communication procedures.

---

## 📍 Portland Venue Recommendations

The following community-appropriate venues have been identified within 2 km of downtown Portland, OR:

| Venue | Type | Address | Distance from Downtown | Notes |
|-------|------|---------|----------------------|-------|
| **Portland Community College – Downtown Center** | Education / Community | 722 SW 2nd Avenue, Portland, OR 97204 | ~0.3 km | Classrooms available for rent; ideal for workshops and training sessions |
| **Portland State University** | University | 1825 SW Broadway, Portland, OR 97201 | ~0.7 km | Has event spaces, auditoriums, and computer labs; community engagement programs available |
| **Portland City Hall** | Civic / Government | 1220 SW 5th Avenue, Portland, OR 97204 | ~0.2 km | Meeting rooms can be booked for public-interest community events |
| **Davies Family Research Library** | Library | 1200 SW Park Avenue, 4th Floor, Portland, OR 97205 | ~0.5 km | Quiet study and meeting spaces; part of Oregon Historical Society |
| **Multnomah County Library – Central** | Library | 801 SW 10th Avenue, Portland, OR 97205 | ~0.8 km | Meeting rooms available for community groups; free to reserve |

### Additional Community-Friendly Spaces to Explore
- **Co-working spaces** (e.g., WeWork, IndieDesk) in the downtown core often have open community event areas
- **Coffee shops with Wi-Fi and group seating** (e.g., The Dusted Cup, Water Avenue Coffee, PDX Starting Grounds) for informal meetups
- **Community/religious halls** (e.g., Campus Christian Ministry, Union Gospel Mission Lifechange Center) frequently rent to community organizations

---

## 🚀 Getting Started

1. **Pick a venue** from the list above and reserve it for your first meetup
2. **Define your workshop topics** using the privacy framework above as a guide
3. **Set up community communications** with proper encryption and consent practices
4. **Invite participants** through transparent, documented channels
5. **Document everything** — apply audit logging and data minimization from day one

---

## 📋 Contributing

We welcome contributions from web security professionals, privacy advocates, educators, and community organizers. Please review our [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing Guide](CONTRIBUTING.md) before getting involved.

---

## 📄 License

This project is open source. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

This toolkit draws on the data privacy and compliance frameworks established by clinical research institutions and HIPAA regulations. The rigor and transparency of clinical trial data handling provides an excellent model for community data practices.