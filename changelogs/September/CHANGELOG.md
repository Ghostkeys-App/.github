# GhostKeys Platform Changelog — Aug–Sep 2025

> **Cut date:** 2025-09-22 (Europe/London)  
> **Scope:** ~100 commits across vault canister, UI components, SDK, and factory updates  
> **Summary:** Major platform stability improvements with stable storage migration, vetKD key flows, Chrome extension MVP, iframe integration, and comprehensive documentation updates.

## 🔐 Vault Canister
- Migrated to `StableBTreeMap` for upgrade-safe storage of spreadsheets, logins, and secure notes
- Enhanced data model with cascading deletes and rich column metadata
- Implemented global sync APIs and vault discovery endpoints
- Delivered vetKD integration for secure key management
- Fixed WASM builds and endianness handling
- Added comprehensive regression test suite

## 🖥️ UI Components
- Partner iframe handshake with secure `IdpPopup` windowing and themed embeds
- Chrome extension MVP with credential flows and runtime messaging
- Multi-profile settings overlay with improved UX
- Enhanced vault SDK adapters for plug-in consumption
- Quality-of-life improvements for spreadsheets and login handling

## 📦 SDK (v1.1.8)
- Initial release of Ghostkeys Lean Serial Protocol
- Test-driven serializer implementation
- ES module exports for npm/TypeScript compatibility
- Comprehensive documentation of data structures
- Built serializers for core data types:
  - Spreadsheets and columns
  - Login metadata
  - Secure notes
  - Global sync payloads

## 🏭 Factory Canister
- Maintained stability with ongoing vault releases
- Added `delete_user` endpoint for data hygiene
- Enhanced operational tooling

## QA Focus
- Verify stable storage migration paths
- Test vetKD key derivation flows
- Exercise Chrome extension installation and usage
- Validate iframe origin checks and messaging
- Confirm SDK serializer compatibility
- Monitor profile switching with pending edits

---

_This changelog consolidates UI, backend, and SDK changes landed after 2025-08-01. See component-specific changelogs for detailed commit histories._