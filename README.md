# What is This?

The Angular team has a roadmap on their site, but it gives a very broad overview of many things.
The goal of this document is to provide more details about the progress of every initiative in the roadmap.

PRs are welcome!

# Key

| Status | Indicator |
|--|--|
| Done | ✅ |
| In Progress | 🚧 |
| No public movement | 🤫 |

# In Progress

## Improve test times and debugging with automatic test environment tear down

The option to opt-in to this behavior was added [here](https://github.com/angular/angular/pull/42566), and is available starting in Angular 12.1.

There is an [open PR](https://github.com/angular/angular/pull/43353) to make this the default, probably in 13.0.

## ✅ Deprecate and remove IE11 support
This includes the removal of many workarounds in Angular, Angular CLI, and Angular Material. The biggest one is the [removal of differential loading](https://github.com/angular/angular-cli/pull/21467), which has been merged.

There may be more workarounds removed, but IE11 support is officially gone in the early 13.0 betas.


## ✅ Leverage ES2017+ as the default output language
In Angular 12 ([this PR](https://github.com/angular/angular-cli/pull/19871)), they downlevel async/await, so that there are no longer zone.js issues. In [this PR](https://github.com/angular/angular-cli/commit/81129e12d0ae4cbaeb5ab537facb7990be9b8b45), released in Angular 12.0 , the default browser target for new projects was updated to 2017.

## 🤫 Revamp performance dashboards to detect regressions

[This](https://github.com/angular/angular/pull/41125) seems to be related to collecting performance information, but I'm not sure if it's related to this milestone or not.


## 🚧 Enhanced Angular Material components by integrating MDC Web

Available in [Material Experimental](https://github.com/angular/components/tree/master/src/material-experimental). Seems to be close, but unlikely to become the default in 13.0. More details on status in [Angular Components README](https://github.com/angular/components/tree/b8d83cb0f4d990a1cb8a976b2383817b304e4dcd#what-were-working-on-now-q1-2021)

## Angular component accessibility
This will most likely just be a collection of smaller issues. You can see a11y issues merged since July 2021 [here](https://github.com/angular/components/issues?q=label%3Aa11y+is%3Aclosed+merged%3A%3E%3D2021-07-01+)

## 🚧 Remove legacy View Engine

[here](https://github.com/angular/angular-cli/pull/20434), [here](https://github.com/angular/angular-cli/pull/20443) and [here](https://github.com/angular/angular-cli/pull/20397).

I think more things can still be removed because even if libraries are still in VE, ngcc will convert it to ivy-compatible code.

[Removing the JIT compiler](https://github.com/angular/angular/issues/43133) is a part of this, but there is only an RFC for doing it eventually, so I don't think this will happen soon. There are many exciting things mentioned in the RFC, with links to other RFCs that have more details:
* [localized compilation](https://github.com/angular/angular/issues/43165)
* [Out-of-band type-checking](https://github.com/angular/angular/issues/43131)
* [View composition APIs](https://github.com/angular/angular/issues/43120)

## 🤫 Publish guides on advanced concepts

No Public Movement

## 🚧 Update our e2e testing strategy

Protractor is now deprecated. No other movement, but something else must be planned since it's still "In Progress"

## ✅ Angular libraries use Ivy
[RFC](https://github.com/angular/angular/issues/38366)

[GitHub Project Board](https://github.com/orgs/angular/projects/2)

The Angular Links has been available since 11.1. see [this article](https://blog.ninja-squad.com/2021/01/27/angular-linker/).

The partial compiler is [the default setting](https://github.com/angular/angular-cli/pull/20470) in Angular 13 libraries. There is [a migration](https://github.com/angular/angular-cli/pull/21616) to update existing projects.

## 🚧 Ensure smooth adoption for future RxJS changes (v7 and beyond)

[this PR](https://github.com/angular/angular/pull/42991) allows rxjs 7 as a peer dependency in 12.2.x. Based on the comment, I assume RxJS 7 will be required in Angular 13.

## Simplified Angular mental model with optional NgModules

[This PR](https://github.com/angular/angular/pull/42831) shows a rough prototype from someone on the team. The API will likely change a ton.

# Future
(Items with no public movement have been excluded)

## Better developer ergonomics with strict typing for @angular/forms
In [this video](https://www.youtube.com/watch?v=FbJLC7GxAAs), Minko teased that he was meeting with the team about type-safe forms. (I'm pretty sure I remember this, but sorry I did not find the timestamp)

## Leverage full framework capabilities with Zone.js opt-out

[This PR](https://github.com/angular/angular/pull/43081) seems to take a stab at allowing this, but I cannot tell if this is the approach that will be used.

# Angular 12

The above list shows the roadmap for the Angular 13 release cycle. For details on Angular 12 changes, [see here](./angular-12.md)
