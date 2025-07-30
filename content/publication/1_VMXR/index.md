---
title: 'VMXR: a EUD Environment for Virtual Merchandizing in XR'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Carlo Nuvole
  - Davide Spano

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['Master Thesis']

# Publication name and optional abbreviated publication name.
publication: 'University of Cagliari' #In Joint Proceedings of the Workshops, Work in Progress Demos and Doctoral Consortium at the IS-EUD 2023 co-located with the 9th International Symposium on End-User Development (IS-EUD 2023), Cagliari, Italy, June 6-8, 2023
publication_short: '' #In *ICW*

abstract: The VR user market is growing year by year. For this reason, an increasing number of ama- teur individuals are becoming more interested in working in this field. However, due to the intrinsic difficulties of development, they will face many difficulties. <br>This thesis presents the work done on a project called Virtual Merchandising and eXtended Reality (VMXR) which aims to support these inexperienced users. By shifting some tasks to developers, it empowers end-users to design, and furnish interactive virtual environments. The tool embodies the concept of end-user development, enabling non-programmer users to perform actions that would typically require technical or specialized knowledge, without the need for such expertise.

# Summary. An optional shortened abstract.
summary: This thesis presents VMXR, a tool enabling non-programmers to create interactive virtual environments by simplifying development tasks, supporting the growing amateur VR user market through end-user development principles.

tags:
  - eXtended Reality
  - End-User Development
  - Event-Condition-Action Rules

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1ganJHeGji6F9UaTBIcaoHLOgN2YUyrJm/view?usp=drive_link'
url_slides: 'https://docs.google.com/presentation/d/1l_QyPFnnRSEaHqU7zh7haHioqggWkU7y/edit?usp=sharing&ouid=116157388079775457519&rtpof=true&sd=true'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'TODO Caption'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - EUD4XR

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

# Short Intro
VMXR is a Proof of Concept study, carried out in collaboration with the company Techedge, that advances the support for non-developer users in creating virtual showcase environments. VMXR adapts the methodology used in ECArules4All to create a workflow among developers and non-developer users (Environment Configurator, and Experience Configurator) in a fully web-based environment.

Even though VMXR tries to maximize the support towards non-programmer users (environment configurator, experience configurator), they cannot do all the work alone: there is still a need for a Developer that takes care of performing some tasks on Unity, the game engine to the base of VMXR.

The Environment Configurator is a non-developer figure, potentially an interior designer, which logs in to the VMXR platform to design the structural content of generic virtual environments and to furnish them with generic content.

The Experience Configurator is another non-developer figure, which logs in to the VMXR platform to personalize a generic content, created by an environment configurator, with specific domain content and custom interactions to create a tailored interactive XR experience.

An XR experience can be enjoyed by final users always through the VMXR platform.