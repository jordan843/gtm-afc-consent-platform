# AfC - Consent Management Platform for Google Tag Manager

[![AfC Logo](https://adsforchange.co/wp-content/uploads/2025/04/logo-Ads-for-Change-vert-png-1-e1750931275367-1536x245.png)](https://adsforchange.co)

**A complete GDPR-compliant Consent Management Platform (CMP) template for Google Tag Manager**

This tag template provides a full-featured consent banner with:
- Complete **Google Consent Mode v2** support
- Region-specific defaults (EEA, UK, Switzerland, Norway, Iceland, Liechtenstein)
- **IAB TCF 2.2** compatibility
- Consent restoration from existing cookies/localStorage
- URL passthrough and ads data redaction options
- Native integration with GTM consent APIs

Perfect for websites needing RGPD compliance with easy setup in GTM.


## Features

- Full Google Consent Mode v2 (ad_storage, analytics_storage, ad_user_data, ad_personalization, etc.)
- Automatic region detection with customizable GDPR regions
- Default consent states (denied/granted per region)
- IAB TCF 2.2 support (optional)
- Consent cookie management (reading/writing)
- Debug mode for testing
- Easy integration – no custom code required

## Installation

### Preferred: From the Community Template Gallery
1. In Google Tag Manager, go to **Templates** > **Search Gallery**
2. Search for "AfC - Consent Management Platform"
3. Click **Add to workspace** > **Add**

### Manual installation (for testing)
1. Download `template.tpl` from this repository
2. In GTM: **Templates** > **New** > Three dots > **Import**
3. Select the downloaded `template.tpl`
4. Save and agree to the Community Template Gallery Terms of Service

## Configuration

1. Create a new tag in GTM
2. Choose **AfC - Consent Management Platform** as tag type
3. Fill in:
   - **CMP ID**: Your unique ID from Ads for Change (provided by AfC)
   - **API URL**: Usually `https://nzkzahxktzncvosefdul.supabase.co/functions/v1` (provided by AfC)
   - Enable region-specific settings and list GDPR regions if needed
   - Set default consent states
   - Enable IAB TCF 2.2 if required
4. Trigger: Use **Consent Initialization** (recommended) or **All Pages**

For detailed setup, see our [full documentation](https://adsforchange.co/agence)

## Support

- Website: [https://adsforchange.co](https://adsforchange.co)
- Documentation: [https://adsforchange.co/documentation](https://adsforchange.co/agence)
- Contact: hello@adsforchange.co

## License

Apache License 2.0

---

## Version française

**AfC - Plateforme de Gestion de Consentement pour Google Tag Manager**

Bandeau de consentement RGPD complet avec :
- Support total Google Consent Mode v2
- Gestion par région (EEE, UK, Suisse, etc.)
- Compatibilité IAB TCF 2.2
- Restauration du consentement via cookies

Installation et configuration identiques à ci-dessus.

Contact : hello@adsforchange.co
