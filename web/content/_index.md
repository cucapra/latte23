+++
+++

LATTE is a venue for discussion, debate, and brainstorming about language-oriented approaches to hardware acceleration.
The focus is on new languages and tools that aim to let domain specialists, not just hardware experts, produce efficient accelerators.
See the [Call for Participation][cfp] for more details.

LATTE '23 is co-located with [ASPLOS '23][asplos-23].
It will happen on Sunday, March 26, 2023 in Vancouver, BC, Canada.

[asplos-23]: https://asplos-conference.org/
[cfp]: @/cfp.md

## Registration

To attend LATTE, please [register for ASPLOS][asplos-reg].
Choose the option to attend (at least) one day of workshops/tutorials, and check the box for LATTE on the second page of the registration form.

[asplos-reg]: https://asplos-conference.org/attend/

## Tentative Program

| Time (PST) | Event |
|-------------|-------|
| {{time(t="9am", l="9–9:15am")}} | Opening & Introductions |
| {{time(t="9:15am", l="9:15–10:15am")}} | [Keynote by Gilbert Bernstein](#keynote) |
| {{time(t="10:15am", l="10:15–10:30am")}} | Break |
| {{time(t="11am", l="11–11:30am")}} | Session 1 |
| {{time(t="11:30am", l="11:30am–12:00pm")}} | Discussion & Open Mic |
| {{time(t="12pm", l="12:00–1:30pm")}} | Lunch |
| {{time(t="1:30pm", l="1:30–2:45pm")}} | Session 2 |
| {{time(t="2:45pm", l="2:45-3pm")}} | Break |
| {{time(t="3pm", l="3–3:30pm")}} | Session 3 |
| {{time(t="3:30pm", l="3:30–4pm")}} | Discussion |

## Keynote

**Performance vs. Correctness When Writing Low-Level HPC Code**  
[Gilbert Bernstein](http://www.gilbertbernstein.com), University of Washington

Most applications benefiting from accelerators (especially ML accelerators) rely on hand-optimized high-performance kernel libraries to get access to new hardware, and ensure a high level of performance (e.g. BLAS, CuDNN, etc.). However, these kernel libraries are still written and optimized by hand, at great expense using low-level C and assembly code. This is because the performance engineers who write this code, (like the hardware designers on the other side of the ISA from them) require control over the design. What if we designed programming languages specially tailored to the needs of these programmers?

First, I will discuss performance and correctness.  Should we think of this as a tradeoff (as the talk title implies) or two halves of the same whole?  Then, I will discuss two different “user-scheduled” languages we’ve built to achieve both performance and correctness in HPC kernel programming. (1) Exo is an imperative language which turns the compiler “inside out” by externalizing control of code optimization directly to the user, and by replacing hardware-specific backends (the compiler writers’ responsibility) with user-level libraries (the performance engineers’ responsibility). (2) ATL is a simple functional tensor language, which we have embedded in Coq. Rewrites of ATL programs thereby become lemmas, and user-scheduling directives become proof tactics. These languages match the performance of highly tuned linear algebra, neural net and image processing kernels by using formal verification machinery to expedite the existing optimization process of low-level software performance engineers.

## Talks

{{ program() }}

<div class="committee">

<div class="pc">
<h2>Program Committee</h2>

- [Ang Li](https://ece.princeton.edu/people/ang-li), Princeton
- [Bo-Yuan Huang](https://bo-yuan-huang.github.io), Intel
- [Clément Pit-Claudel](https://pit-claudel.fr/clement/), EPFL
- [Hanchen Ye](https://hanchenye.com), UIUC
- [Hongbo Rong](https://sites.google.com/view/hongborong), Intel
- [Jianyi Cheng](https://jianyicheng.github.io), Imperial College London
- [Jie Wang](https://vast.cs.ucla.edu/people/student/jie-wang), Amazon
- [John Demme](http://www.cs.columbia.edu/~jdd/), Microsoft
- [Jose Renau](https://users.soe.ucsc.edu/~renau/), UC Santa Cruz
- [Julian Oppermann](https://www.esa.informatik.tu-darmstadt.de/team/jo), TU Darmstadt
- [Michael Christensen](https://mdko.github.io), Meta
- [Ross Daly](https://web.stanford.edu/~rdaly525/), Stanford
- [Shail Dave](https://sites.google.com/view/shail/), Arizona State University
- [Thomas Bourgeat](https://people.csail.mit.edu/bthom/), EPFL
- [Yann Herklotz](https://yannherklotz.com/), Imperial College London

</div>

<div class="organization">
<h2> Organizing Committee </h2>

- [Stephen Neuendorffer](https://sites.google.com/site/sneuendorffer/), AMD
- [Rachit Nigam](https://rachitnigam.com), Cornell
- [Adrian Sampson](https://adriansampson.net), Cornell
- [Zachary Sisco](https://zsisco.github.io), UC Santa Barbara
- [Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/), Cornell

</div>
</div>
