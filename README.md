# Grammarly Prompt Removal Script

![License](https://img.shields.io/badge/License-MIT-blue.svg)  [![Documentation](https://img.shields.io/badge/Documentation-red.svg)](https://geotrek.readthedocs.io/)  ![Platform](https://img.shields.io/badge/Platform-Windows%7CMac%7CLinux-green) &nbsp; ![Status](https://img.shields.io/badge/Status-Experimental-orange) 




<a href="https://geotrek.readthedocs.io/" rel="nofollow"><img alt="Documentation" src="https://img.shields.io/badge/Documentation-red.svg" style="max-width:100%;"></a>
<a href="https://demo-admin.geotrek.fr/" rel="nofollow"><img alt="Geotrek Admin demo" src="https://img.shields.io/badge/Demo-purple.svg" style="max-width:100%;"></a>
<a href="https://matrix.to/#/%23geotrek:matrix.org" rel="nofollow"><img alt="Chat Matrix" src="https://img.shields.io/badge/Chat-blue.svg" style="max-width:100%;"></a>
<a href="https://groups.google.com/g/geotrek-fr" rel="nofollow"><img alt="Forum Google Group" src="https://img.shields.io/badge/Forum-brightgreen.svg" style="max-width:100%;"></a>
---

## Overview
This script is designed to remove Grammarly's premium upgrade prompts and extension installation messages, providing a cleaner user experience.

## Features
- **Removes elements** with class names containing `premium` or `upgrade`
- **Removes extension installation prompts**
- **Disables and hides buttons** that trigger upgrade or installation dialogs
- **Runs immediately** to clean existing prompts
- **Monitors DOM changes** with a `MutationObserver` to remove dynamically added prompts

## Usage
Inject the script into the Grammarly desktop application using tools like:
- **Tampermonkey** (Browser extension for custom scripts)
- **Other script injection tools**

> **Note:** Adjustments may be needed based on Grammarly's updates or specific implementations.

## Important Considerations
- **Terms of Service:** Modifying or bypassing features may violate Grammarly's terms. Proceed with caution.
- **Python Alternative:** You can create a Python script to modify Grammarly's installation files, though this is complex and risky.
- **Ethical Usage:** Consider purchasing a Grammarly subscription for full access or use the free features as intended.

## License
This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer:** This script is for educational purposes only. Use responsibly.


