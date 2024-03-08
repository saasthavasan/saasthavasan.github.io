---
title: 'Columbus: Android App Testing Through Systematic Callback Exploration'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Priyanka Bose
  - Dipanjan Das
  - admin
  - Sebastiano Mariani
  - Ilya Grishchenko
  - Andrea Continella
  - Antonio Bianchi
  - Christopher Kruegel
  - Giovanni Vigna

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-02-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 45th International Conference on Software Engineering (ICSE)
publication_short: In ICSE 2023

abstract: With the continuous rise in the popularity of Android mobile devices, automated testing of apps has become more important than ever. Android apps are event-driven programs. Unfortunately, generating all possible types of events by interact- ing with an app’s interface is challenging for an automated testing approach. Callback-driven testing eliminates the need for event generation by directly invoking app callbacks. However, existing callback-driven testing techniques assume prior knowledge of An- droid callbacks, and they rely on a human expert, who is familiar with the Android API, to write stub code that prepares callback arguments before invocation. Since the Android API is very large and keeps evolving, prior techniques could only support a small fraction of callbacks present in the Android framework. <br> In this work, we introduce COLUMBUS, a callback-driven test- ing technique that employs two strategies to eliminate the need for human involvement; (i) it automatically identifies callbacks by simultaneously analyzing both the Android framework and the app under test; (ii) it uses a combination of under-constrained symbolic execution (primitive arguments), and type-guided dynamic heap introspection (object arguments) to generate valid and effective inputs. Lastly, COLUMBUS integrates two novel feedback mechanisms—data dependency and crash-guidance— during testing to increase the likelihood of triggering crashes and maximizing coverage. In our evaluation, COLUMBUS outperforms state-of-the-art model-driven, checkpoint-based, and callback- driven testing tools both in terms of crashes and coverage.

# Summary. An optional shortened abstract.
summary: Android apps are event-driven, and generating various types of events through app interfaces for testing purposes can be challenging. To address this, in this paper we introduce COLUMBUS, a callback-driven testing technique. COLUMBUS automatically identifies callbacks, uses symbolic execution and dynamic heap introspection to generate valid inputs, and incorporates feedback mechanisms to enhance crash detection and coverage. In evaluations, COLUMBUS outperforms existing testing tools in terms of both crashes and coverage.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
