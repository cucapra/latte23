+++
template = "page.html"
+++

LATTE '23 is a workshop co-located with [ASPLOS '23][asplos-23].
It will happen on Sunday, **March 26, 2023** in Vancouver, BC, Canada.

## Submissions

Submit your **2-page position paper** via HotCRP. Important dates:

- Paper submission:  **Feburary 7, 2023**
- Author Notification: **Feburary 21, 2023**
- Workshop: **March 26, 2023**

**Note.** The audience attending LATTE is already very specialized and does
not require motivating specialized hardware accelerators. We strongly encourage
authors to keep their introduction sections very focused and short and utilize
the space for more detailed technical content.

## Registration
To attend LATTE, please [register for ASPLOS][asplos-reg].
Choose the option to attend (at least) one day of workshops/tutorials, and check the box for LATTE on the second page of the registration form.


## Call for Participation

**Scope.**
LATTE is a venue for debate and discussion at the intersection of hardware acceleration, programming languages, and system design. Unlike a conference, we encourage authors to delve "into the weeds" of their systems, talk about design choices, pragmatics, and user experiences. The scope of the workshop includes. but is not limited to:

- Domain-specific languages, type-systems, and compilers for *generating hardware accelerators* as well as *programming accelerators*
- Verification, testing, and debugging techniques
- Virtualization schemes for specialized & reconfigurable hardware
- Build and integration systems for accelerators

LATTE solicits short position papers that need not fit the mold of a traditional publication:

- Early, in-progress research snapshots
- Experience reports on building or deploying accelerators and the tools involved
- Essays advocating for or against a general approach
- Retrospectives on past efforts on tools, languages, and techniques for accelerator design
- Calls for solutions to open challenges in the area (questions without answers)
- Demonstrations of real systems (to be shown off in a live demo at the workshop)

**Motivation.**
Hardware acceleration is a key part of combating the stagnation of hardware performance scaling. Implementing accelerators with state-of-the-art hardware design flows, such as traditional HDLs and current HLS tools, remains a specialized task requiring EE training, proprietary toolchains, and extremely slow compile-edit-run cycles. While traditional approaches *might* be appropriate for developing general-purpose CPUs that will ship millions of units, they are an impediment to popularizing acceleration for the “long tail” of applications that could benefit from special-purpose hardware. With new language designs and new techniques inspired by traditional compilers research, there is an opportunity to turn accelerator construction from a years-long enterprise into a weekend project.


### How to Participate

The primary goal of the workshop is to enable discussion. It will accept **2-page position papers**.
The workshop will allocate short time slots to the papers, each paired with a discussion following [SNAPL][]'s discussion format:
“table discussion” where small breakout groups will discuss the paper, followed by plenary Q&A.

Position paper submissions will undergo peer review by a program committee of interdisciplinary experts working on both high-level (languages, compilers, drivers) and low-level (circuit optimization, interconnect design) problems in the area.

**Formatting.** Papers should use the two-column [the formatting guidelines for SIGPLAN conferences][sigplanconf] (the `acmart` format with the `sigplan` two-column option) and not exceed 2 pages, excluding references. Review is single-blind, so please include authors' names on the submitted PDF.
We provide [a latex example][format-example] that contains the correct formatting.

Paper submission will is via [HotCRP][].
The accepted papers will not be published in a proceeding—PDFs will instead appear on the workshop's website.


<div class="committee">

<div class="pc">
<h2>Program Committee</h2>

TBA

</div>

<div class="organization">
<h2> Organizing Committee </h2>

- [Stephen Neuendorffer](https://sites.google.com/site/sneuendorffer/)
- [Rachit Nigam](https://rachitnigam.com)
- [Adrian Sampson](https://adriansampson.net)
- [Zachary Sisco](https://zsisco.github.io)
- [Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/)

</div>
</div>

[snapl]: http://cs.brown.edu/~sk/Memos/Conference-Discussion-Format/
[hotcrp]: https://latte.cs.cornell.edu/
[sigplanconf]: https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart.pdf
[asplos-23]: https://asplos-conference.org/
[latte-21]: https://capra.cs.cornell.edu/latte21/
[format-example]: https://github.com/cucapra/latte22/tree/main/camera-ready
[asplos-reg]: https://asplos-conference.org/attend/
