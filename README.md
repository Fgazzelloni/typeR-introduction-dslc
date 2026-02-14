# typeR

Simulating Live Coding for Teaching and Technical Talks

This repository accompanies the DSLC.io Project Club talk introducing the typeR package.

The session presents the motivation, design, and implementation of typeR, an R package that simulates realistic live coding in the R console.

⸻

## 🎯 Talk Context

Live coding is powerful — but risky.

In teaching and technical presentations, we face a recurring trade-off:
	•	Static code is safe but removes cognitive flow
	•	Live coding is engaging but prone to errors

This talk explores how typeR addresses that dilemma.

⸻

## 📽 Presentation Slides

The full slide deck from the Project Club session is available here:

👉 Download the presentation (PDF)￼

The slides cover:
	•	The live coding dilemma
	•	Design philosophy
	•	Core functionality (typeR() and typeRun())
	•	Quarto integration
	•	Teaching and presentation use cases
	•	Design principles and future direction

⸻

## 🧠 What is typeR?

typeR is an R package that:
	•	Simulates character-by-character typing
	•	Optionally executes code while typing
	•	Works with .R, .Rmd, and .qmd files
	•	Integrates directly with the R console and RStudio

The goal is not animation —
the goal is controlled realism for technical communication.

⸻

## 🔎 Minimal Example

library(typeR)

typeR("script.R", delay = 0.05)

Typing and execution:

typeRun("script.R", delay = 0.05)


⸻

## 📦 Installation

From CRAN:

install.packages("typeR")

From GitHub:

devtools::install_github("Fgazzelloni/typeR")


⸻

## 💬 Discussion Points from the Talk

During the Project Club session, we discuss:
	•	When live coding fails
	•	The psychology of teaching code
	•	Why process matters more than static output
	•	Design decisions behind minimal abstraction
	•	Trade-offs in simulation vs real-time execution

⸻

## 🔗 Links

GitHub repository:
https://github.com/Fgazzelloni/typeR

Documentation:
https://fgazzelloni.github.io/typeR

⸻

## About the Author

**Federica Gazzelloni**
Statistician, Actuary, and R educator
Lead Organizer – R-Ladies Rome & Rome R Users Group
