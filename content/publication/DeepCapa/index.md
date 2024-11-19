---
authors:
  - admin
  - Hojjat Aghakhani
  - Stefano Ortolani
  - Roman Vasilenko
  - Ilya Grishchenko
  - Christopher Kruegel
  - Giovanni Vigna

title: 'DeepCapa: Identifying Malicious Capabilities in Windows Malware'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-12-14T00:00:00Z'
publishDate: '2024-11-15T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 40th Annual Computer Security Applications Conference
publication_short: In ACSAC 2024

# Summary. An optional shortened abstract.
summary: DeepCapa is an automated post-detection framework that identifies and maps potentially malicious capabilities in malware to the code that implements these capabilities. It proposes a novel feature engineering approach that statically extracts API-call sequences from multiple memory snapshots taken during a sample’s dynamic execution. This approach allows for more comprehensive code coverage and effectively counters anti-sandbox techniques. Deepcapa also proposes a neural network architecture to not only accurately detects capabilities but also provide interpretable detections.

abstract: Malware detection and classification have been the focus of extensive research over many years. However, less effort has been devoted to developing post-detection systems that identify specific malicious capabilities (or behaviors) in malware.Such systems play a critical part in identifying and mitigating the damage caused by malware attacks. Unfortunately, current methods for identifying malware capabilities involve substantial manual reverse engineering efforts and context switching between multiple different tools, which slows down an investigation and gives attackers an advantage. <br> In this paper, we propose DeepCapa, an automated post-detection system that uses deep learning to identify potentially malicious capabilities in malware in the form of MITRE ATT\&CK techniques. Our system operates on sequences of API calls, statically extracted from the memory snapshots taken at key points during the execution of malware. Our results demonstrate that DeepCapa can accurately identify malicious capabilities,  achieving a precision of 95.80% and a recall of 93.76% across 29 different  MITRE ATT&CK techniques.


tags: [Malware Analysis, AI, Neural Networks, Program Analysis]

# Display this page in the Featured widget?
featured: true
---


<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
