# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a documentation repository for TallyPod's privacy policy. TallyPod is a financial tracking mobile application developed by Alexander Urquijo (cephalopodlabs@gmail.com) based in Panama. The repository contains legal documentation for compliance with international privacy regulations.

## Repository Structure

```
docs/
  privacy_policy_en.md  # English privacy policy
  privacy_policy_es.md  # Spanish privacy policy (Español)
```

## About TallyPod

TallyPod is a privacy-focused expense and income tracking application with the following key characteristics:

**Core Features:**
- Expense and income tracking with categories
- Receipt OCR scanning (on-device using Google ML Kit)
- Household sharing functionality
- Cloud sync via Supabase
- CSV data export
- Biometric protection (fingerprint/Face ID)

**Privacy Architecture:**
- No tracking cookies or analytics services
- No location collection
- No data selling to third parties
- On-device OCR processing (not sent to external servers)
- Row-level security (RLS) in Supabase
- HTTPS/TLS encryption for data transmission
- Google OAuth 2.0 authentication

**Technology Stack:**
- Backend: Supabase (PostgreSQL with encryption)
- Authentication: Google Sign-In
- OCR: Google ML Kit (on-device processing)
- Local Storage: Encrypted SQLite

**Legal Compliance:**
- GDPR (General Data Protection Regulation - EU)
- CCPA (California Consumer Privacy Act - USA)
- Law 81 of 2019 (Panama Personal Data Protection Law)
- Google Play Store Developer Policies
- Apple App Store Guidelines

## Working with Privacy Policy Documents

**Important Principles:**
1. Maintain parity between English and Spanish versions - updates to one must be reflected in the other
2. Ensure compliance with all listed regulations (GDPR, CCPA, Panama Law 81)
3. Keep developer contact information accurate (cephalopodlabs@gmail.com)
4. Update "Last Updated" date when making changes
5. Privacy policy must be accurate regarding what data is collected and how it's used

**Bilingual Requirement:**
Both `privacy_policy_en.md` and `privacy_policy_es.md` must contain equivalent information. When updating one, always update the other accordingly.

**Key Sections to Preserve:**
- Information collection and usage practices
- Third-party services (Google Sign-In, Supabase, Google ML Kit)
- User rights under different jurisdictions
- Security measures and data retention policies
- Contact information and legal compliance statements

## Git Operations

This is a standard git repository with:
- Main branch: `main`
- Standard git workflow (add, commit, push)
- No special build or deployment processes required

When making changes, ensure commit messages clearly describe what was updated in the privacy policy.
