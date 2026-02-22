# HEXSTRIKE Modules — Independent Component Repository

## Overview
This repository contains modular components for the HEXSTRIKE Mission Control dashboard. Each module is a self-contained feature that can be updated independently from the main dashboard.

## Module Categories

### Bug Bounty Modules
- `bug_bounty_module_marketplace` - Module marketplace for installing new features
- `bug_bounty_api_&_integrations_config` - HackerOne, Bugcrowd, Intigriti API config
- `bug_bounty_recon_automation_config` - Recon workflow automation settings
- `bug_bounty_scope_manager` - Target scope and out-of-scope management
- `bug_bounty_dork_template_library` - Google dork templates for reconnaissance
- `bug_bounty_osint_&_caido_workspace` - OSINT tools and Caido integration
- `bug_bounty_attack_surface_map_1` - Attack surface visualization (version 1)
- `bug_bounty_attack_surface_map_2` - Attack surface visualization (version 2)

### RedClaw Modules
- `redclaw_poc_script_generator` - PoC script templates and generation
- `redclaw_nuclei_template_ide` - Nuclei template editor with AI assistance
- `redclaw_operational_dashboard` - Red team operations dashboard
- `redclaw_remediation_tracker` - Vulnerability remediation tracking
- `redclaw_asset_history_timeline` - Asset change history and timeline view

### Vulnerability Modules
- `p1_vulnerability_deep-dive_view` - Deep dive into critical P1 vulnerabilities
- `vulnerability_remediation_tracker` - Cross-platform remediation tracking

### Nuclei Integration
- `nuclei_template_ide_&_ai_assistant` - Nuclei template IDE with AI code generation

## Module Structure

Each module contains:
- `code.html` - Main interface and logic
- Module-specific assets and configuration

## Installation

Modules are auto-loaded by the main dashboard (`HEXSTRIKE-WORKING.html`).

## Development

Edit module code in this repo, commit, and the dashboard will auto-scan for updates.

---

**Total Modules: 12 active components**  
**Dashboard:** https://github.com/PWAEngine/hexstrike-dashboard  
**Modules:** https://github.com/PWAEngine/hexstrike-modules