---
menu:
  notes:
    name: Définitions
    identifier: notes-angular-definitions
    parent: notes-angular
    weight: 10
---

# Angular definitions

<!-- Component -->

{{< note title="Component" >}}

A component is composed of:

- A **template** (HTML view layout)
- A **class** (Containing attributes/properties and methods/logic to support the view)
- **Metadata** (Defined through the `@Component` decorator)

Basically, we create a component by page OR by reusable UI element.

{{< /note >}}

<!-- Directive -->

{{< note title="Directive" >}}

Custom HTML element or attribute used to power up and extend our HTML.
Basically a class with a `@Directive` decorator.

There are two types of directive :

- **Structural** : Alter the layout by adding, removing, replacing elements in the DOM (*ngIf, *ngFor …)

- **Attribute** : Alter the appearance or behaviour of an existing element
  {{< /note >}}
