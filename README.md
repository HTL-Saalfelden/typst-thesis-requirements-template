# HTL Saalfelden Thesis Requirements Template

A Typst template for creating thesis requirements specifications (Pflichtenheft) for HTL Saalfelden diploma theses. Supports German and English.

## Getting Started

Import the template from the Typst Universe preview:

```typ
#import "@preview/htl-saalfelden-thesis-requirements:0.1.0": htl_doc

#show: htl_doc.with(
  title: "Your Thesis Title",
  subtitle: "Detailed Topic Description",
  school-year: "2025/26",
  class: "5AHIF",
  department: "Informatik",
  authors: "Max Mustermann",
  candidates: (
    (name: "Max Mustermann", class: "5AHIF", task: "Hauptverfasser"),
  ),
  supervisors: (
    (title: "Prof.", name: "Lastname"),
  ),
  due_date: "DD.MM.YYYY",
  lang: "de",
)
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./thumbnail-dark.svg">
  <img src="./thumbnail-light.svg" alt="HTL Saalfelden Thesis Requirements Template">
</picture>

## Installation

Use Typst's package manager: `@preview/htl-saalfelden-thesis-requirements`. No local installation needed for the web app.

## Usage

See the included manual (`docs/manual.pdf`) for detailed usage instructions and all available parameters.
