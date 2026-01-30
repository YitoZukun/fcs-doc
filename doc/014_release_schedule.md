## Release Schedule
Updated: January 30, 2026<br><br>
Starting in 2026, the release cycle for FCS will change from the previous quarterly updates to semi-annual updates in April and October (twice a year).<br>

#### 1. Regular releases (major versions)
Major versions that mainly include specification changes, such as adding new features and changing algorithms, will be released twice a year, in April and October.<br>
By changing the release frequency, we aim to further stabilize the quality of each version.

#### 2. Hotfix releases (minor versions)
Once a major version is released, feature set is frozen until the next regular release.<br>
Minor version could include subtle improvements such as UI refinement and bug fixes, will be released as needed (e.g., 24.10.01).
<br>

### Schedule
```{figure} images/fcs_release_timeline_v02.jpg
:width: 80%
:align: center
```

### Upgrading FCS

#### Standard vs LTS
The main difference between standard and LTS version lies in the length of their support period (how long the version would receive minor bug fix), 6 months vs 1 year.<br>
LTS is recommended if the current LTS version meets all your requirements and you work on projects that last for longer than the standard supported period. <br> 

Preview release has been discontinued.

- What is the preview version? <br> 
  Preview versions provides a glimpse of upcoming features of new version of FCS and provide a chance to provide feedback to the developers.<br>
  It is where we release non-critical bug fixes and are subject to constant changes and no support is guaranteed.

#### Compatibility
FCS sessions are forward-compatible unless explicitly noted otherwise; however, backward compatibility is not always guaranteed, especially across major versions (e.g., 26.04, 26.10).<br>
This means you can open FCS sessions created in a previous version of FCS using newer versions. However, once a session is opened in a newer version, it may no longer be possible to open it in an older version of FCS.<br>
Therefore, it is critical to back up your files before upgrading to a newer version of FCS.<br>
We strive to maintain backward compatibility within a major version (e.g., across 24.07.01–24.07.10); however, this is not guaranteed.<br>

#### Steps to upgrade
1. [Export your data](#export-header-target). 
2. Open the exported data using the newly downloaded version of FCS.
