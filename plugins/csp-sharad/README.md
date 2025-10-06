<!-- 
SPDX-FileCopyrightText: German Aerospace Center (DLR) <cosmoscout@dlr.de>
SPDX-License-Identifier: CC-BY-4.0
 -->

# Sharad rendering for CosmoScout VR

A CosmoScout VR plugin which renders radar datasets acquired by the Mars Reconnaissance Orbiter. The SHARAD profiles are rendered inside of Mars, the Martian surface is made translucent in front of the profiles.

## Configuration

This plugin can be enabled with the following configuration in your `settings.json`:

```javascript
{
  ...
  "plugins": {
    ...
    "csp-sharad": {
      "filePath": <path to folder with SHARAD data>
    }
  }
}
```

**More in-depth information and some tutorials will be provided soon.**

<!-- Auto-update: 2025-10-07T02:36:36.128813 -->
