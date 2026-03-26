# Privacy Policy for Earthquake Monitor

**Last updated:** March 25, 2026

---

## 1. Introduction

Earthquake Monitor ("the Extension") is a Chrome extension that displays recent earthquakes near your location and provides real-time notifications. This privacy policy explains what data the Extension collects, how it is used, and your rights regarding your data.

---

## 2. Data Collection and Storage

Earthquake Monitor collects and stores only the data necessary to provide its core functionality. All data is stored **locally on your device** using Chrome's `storage.local` API.

### Data Collected:

| Data Type | What It Is | How It's Used |
|-----------|------------|---------------|
| **Location** | Your latitude and longitude | To calculate distances from earthquakes to your position |
| **Settings** | Radius, magnitude threshold, time period, data source, unit preference (km/mi) | To customize your earthquake monitoring |
| **Notification preference** | Whether notifications are enabled | To know if you want to receive alerts |
| **Earthquake data** | Earthquake IDs seen in the last 2 hours | To avoid duplicate notifications |

### What Is NOT Collected:

- ❌ Your IP address
- ❌ Your browsing history
- ❌ Any personally identifiable information
- ❌ Data from other websites
- ❌ Any information sent to external servers (except earthquake data APIs)

---

## 3. How Your Data Is Used

### 3.1. Location Data
Your location is used **only to calculate distances** between you and each earthquake. Location data:
- Is stored locally on your device
- Is never sent to any server (the Extension calculates distances locally)
- Can be reset or changed at any time

### 3.2. Settings and Preferences
All settings (radius, magnitude, time period, data source, unit) are stored locally and used only to filter earthquake data.

### 3.3. Notifications
If you enable notifications, the Extension checks for new earthquakes every 2 minutes. It compares earthquake IDs against previously seen ones to avoid duplicate alerts. This data is stored locally and automatically cleaned up (old IDs are removed after a while).

### 3.4. Earthquake Data from External APIs
The Extension fetches earthquake data from public seismic networks:

| Source | URL | Data Used |
|--------|-----|-----------|
| USGS | earthquake.usgs.gov | Magnitude, location, time, coordinates |
| INGV | webservices.ingv.it | Magnitude, location, time, coordinates |
| EMSC | seismicportal.eu | Magnitude, location, time, coordinates |

**Important:** These third-party services have their own privacy policies. The Extension does not send your location or any personal data to these services — only the date range and minimum magnitude filter.

---

## 4. Third-Party Services

The Extension uses the following third-party services:

### 4.1. OpenStreetMap (Map Display)
The map shown in the Extension is embedded from `openstreetmap.org`. Your location coordinates are included in the map URL to center the map on your area. Please refer to the [OpenStreetMap Privacy Policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy) for information on how they handle data.

### 4.2. Earthquake Data APIs
- **USGS** — [Privacy Policy](https://www.usgs.gov/privacy-policy)
- **INGV** — [Privacy Policy](https://www.ingv.it/privacy)
- **EMSC** — [Privacy Policy](https://www.emsc-csem.org/Privacy.php)

The Extension does not share any personal data with these services.

---

## 5. Permissions

The Extension requests the following permissions:

| Permission | Why It's Needed |
|------------|-----------------|
| `storage` | To save your settings (radius, magnitude, etc.) locally |
| `geolocation` | To get your current location for distance calculations |
| `notifications` | To send you earthquake alerts (only if you enable them) |
| `host_permissions` (earthquake APIs) | To fetch earthquake data from USGS, INGV, and EMSC |

---

## 6. Data Security

- All personal data (location, settings) is stored locally using Chrome's secure `storage.local` API
- No personal data is transmitted to external servers
- Earthquake data is fetched from public APIs but does not include any personal information
- Your location is never shared with earthquake data providers

---

## 7. Your Rights

Since all data is stored locally on your device, you have full control:

- **View:** Your current location and settings are visible in the Extension interface
- **Change:** You can update your location, radius, magnitude threshold, and other settings at any time
- **Disable location:** You can revoke location permission in Chrome settings
- **Disable notifications:** Uncheck the notifications box in the Extension
- **Delete all data:** Uninstall the Extension to remove all locally stored data

---

## 8. Changes to This Policy

We may update this privacy policy from time to time. Any changes will be posted on this page, and the "Last updated" date will be revised. Continued use of the Extension after changes constitutes acceptance of the updated policy.

---

## 9. Contact

If you have any questions about this privacy policy or the Extension's data practices, you can contact:

**Ievgenii Podovinnikov**  
Email: ievgenii.podovinnikov@gmail.com  
Website: https://ievgenii.com

---

© 2026 Ievgenii Podovinnikov. All rights reserved.
