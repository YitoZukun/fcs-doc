## Release Schedule
Updated: January 30, 2026<br><br>
Starting in 2026, the release cycle for FCS will change from the previous quarterly updates to semi-annual updates in April and October (twice a year).<br>

#### 1. Regular releases (major versions)
Major versions that mainly include specification changes, such as adding new features and changing algorithms, will be released twice a year, in April and October.<br>
By changing the release frequency, we aim to further stabilize the quality of each version.

#### 2. About fix releases (minor versions)
Once a major version is released, there will be no major updates with additional features until the next regular release.<br>
Minor version updates, which include minor improvements such as UI changes and bug fixes, will be implemented as needed (e.g., 24.10.01).

<br><br>
<s>FCS follows a quarterly release schedule, on January, April, July, and October. 
Each major version released is supported either for 3 months (standard) or 1 year for Long-term Support(LTS). 
Once released a major version will receive no update beside bug fixes that come as minor version updates (i.e., 24.07.02~)</s>

### Schedule
```{figure} images/fcs_release_timeline_v02.jpg
:width: 80%
:align: center
```

### Upgrading FCS
#### Standard vs LTS vs Preview
The main difference between standard and LTS version lies in the support period, 3 months vs 1 year.<br>
During support period we will issue critical bug fixes to the version once fixed. LTS is recommended if the current supported LTS version meets all your requirements and you work on projects that last for longer than the standard supported period. <br>

Updated: January 30, 2026<br>
Preview release has been discontinued.
<s>Preview versions provides a glimpse of upcoming features of new version of FCS and provide a chance to provide feedback to the developers. It is where we release non-critical bug fixes and are subject to constant changes and no support is guaranteed, you should never use the preview version without making backup of the data. You should only use the preview if and only if you some specific features and you understand the risk. </s>

#### Compatibility
FCS Sessions are forward compatible unless explicit noted otherwise, however backward compatibility is not always guaranteed especially across major version (e.g., 24.07, 24.10). That means, you can open FCS sessions created in a previous version of FCS with newer versions of FCS. However, once opened in a newer version, you might not be able to open the session in an older version of FCS anymore. Hence it is critical for you to backup your files before moving to a newer version of FCS. 
We try to keep session backward compatible as much as possible within a major version (e.g., across 24.07.01~24.07.10) however there is no guarantee. 
In case of using the same FCS session with others, it is critical for you to ensure that your team use the same minor version of FCS.  

#### Steps to upgrade
1. [Export your data](#export-header-target). 
2. Open the exported data using the newly downloaded version of FCS.
