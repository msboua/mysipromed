# MySipromed Legal Documentation Repository

## Project Overview

This repository contains legal documentation for **MySipromed**, a mobile health insurance application developed by **M3S Assurance** (formerly referenced as SIPROMED-ASSISTANCE). The app serves insured members in Côte d'Ivoire, enabling them to manage medical prescriptions, reimbursement claims, and locate healthcare facilities.

## Architecture & Structure

### Document Management Pattern
- **Dual-format approach**: Critical legal documents exist in both Markdown (`.md`) and HTML formats
- **HTML styling**: Uses consistent brand colors (#00973B green, #1B3877 blue) with responsive design
- **Multi-language support**: All content is in French, targeting Ivorian market

### Key Files
- `PRIVACY_POLICY.md` & `privacy-policy.html` - Privacy policy (comprehensive GDPR-style document)
- `TERMS_OF_SERVICE.md` - Terms of service 
- `index.md` - Legacy terms (references old "SIPROMED-ASSISTANCE" branding)

## Content Conventions

### Branding Consistency
- **Current brand**: "M3S Assurance - MySipromed"
- **Legacy references**: Some documents still reference "SIPROMED-ASSISTANCE" (requires updates)
- **App identifier**: "MySipromed" (consistent spelling with capital S)
- **Tagline**: "Votre santé, notre priorité" 💊

### Legal Document Structure
1. **Header with last updated date** (format: "20 novembre 2025")
2. **Numbered sections** with clear hierarchical organization
3. **Highlight boxes** for critical information
4. **Contact sections** with multiple channels (email, phone, address)
5. **Footer** with copyright and branding

### Technical Framework References
Documents mention these technical integrations:
- **Expo**: Mobile development framework
- **EmailJS**: Email service integration  
- **HTTPS/TLS**: Security protocols
- **Push notifications**: User engagement system

## Development Workflows

### Document Updates
When updating legal documents:
1. **Maintain dual formats**: Update both `.md` and `.html` versions
2. **Update timestamps**: Change "Dernière mise à jour" date
3. **Preserve styling**: HTML documents use embedded CSS with brand colors
4. **Cross-reference consistency**: Ensure links between documents work (e.g., `./PRIVACY_POLICY.md`)

### HTML Styling Guidelines
- Use embedded CSS (no external stylesheets)
- Mobile-first responsive design with `@media` queries
- Print-friendly styles with `@media print`
- Consistent color scheme: #00973B (green), #1B3877 (blue), #666 (gray)
- Typography: System fonts with fallbacks

### Contact Information Standards
Always include complete contact details:
- **Privacy**: privacy@m3sassurance.com
- **Support**: support@m3sassurance.com / contact@m3sassurance.com  
- **Phone**: +2250140001010
- **Location**: Abidjan Plateau immeuble delafosse

## Legal Compliance Context

### Data Protection Framework
- **Jurisdiction**: Côte d'Ivoire law applies
- **Data retention**: Medical data (3 years), reimbursement (5 years), usage (12 months)
- **User rights**: GDPR-style rights (access, rectification, erasure, portability)
- **Age restriction**: 18+ only (no minor data collection)

### Healthcare Integration
Documents must account for:
- **Medical data sensitivity**: Prescriptions, reimbursement history
- **Healthcare partnerships**: Doctors, pharmacies, health facilities  
- **Regulatory compliance**: Insurance industry requirements
- **Fraud prevention**: Security and authentication measures

## Key Dependencies & Services

Based on documentation references:
- **Mobile platform**: React Native/Expo framework
- **Authentication**: Insurance card number validation
- **Geolocation**: Pharmacy/facility finder
- **Document storage**: PDF/photo upload capabilities
- **Email services**: EmailJS integration
- **Push notifications**: Medical reminders and alerts

## Common Maintenance Tasks

1. **Quarterly legal review**: Update dates, verify contact information
2. **Brand consistency audit**: Search/replace old "SIPROMED-ASSISTANCE" references  
3. **Cross-platform validation**: Ensure HTML renders correctly on mobile/desktop
4. **Link verification**: Test internal document references
5. **Translation updates**: Maintain French language accuracy for legal terms