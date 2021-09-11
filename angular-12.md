# Angular 12

## ✅ Faster apps by inlining critical styles in Universal applications

RFC: [here](https://github.com/angular/angular-cli/issues/18730)

Introduced: [here](https://github.com/angular/angular-cli/pull/19449)

Enabled By Default: [here](https://github.com/angular/angular-cli/pull/20096)

## ✅ Improve debugging with better Angular error messages

Detailed documentation of errors has been added [here](https://angular.io/errors/NG0100)

## 🚧 Revamp performance dashboards to detect regressions

Added [here](https://github.com/angular/angular/pull/41125)

More added [here](https://github.com/angular/angular/pull/41319)

## ✅ Update our e2e testing strategy

[Protractor deprecation announced](https://github.com/angular/protractor/issues/5502). 
Development will end at the end of 2022.

## 🚧 Angular libraries use Ivy
[RFC](https://github.com/angular/angular/issues/38366)

[GitHub Project Board](https://github.com/orgs/angular/projects/2)

Available in 11.1, see [this article](https://blog.ninja-squad.com/2021/01/27/angular-linker/)

Some more details in [Angular biweekly meeting notes](https://docs.google.com/document/d/1rC5dz7AkCZP813daT_bccbS-20OLmXgBVi50CSKx148/pub) from March 23, 2021.

The partial compiler for libraries won't become default until Angular 13.

## ✅ Ensure smooth adoption for future RxJS changes (v7 and beyond)

No public movement yet. rxjs seems to work fine with Angular 12-next.6 in my simple project.

Here's [one PR](https://github.com/angular/angular/pull/41590) that aims to improve some compatibility with the latest versions of RxJS.

RxJS 7 has been officially released.

## ✅ Transition the Angular language service to Ivy

[GitHub Project Board](https://github.com/orgs/angular/projects/1)

Available in 11.X versions. Enable experimental mode in VS Code extension settings.

In Angular 12, Ivy is the default for Angular Language Service. In my experience it is much better and more stable.

## ✅ Increased security with native Trusted Types in Angular
Available in 11.X. I think all the big parts are done.

Some more PRs in progress [here](https://github.com/angular/angular/pull/40499), but no movement since Jan. 2021.

## 🚧 Enhanced Angular Material components by integrating MDC Web

Available in [Material Experimental](https://github.com/angular/components/tree/master/src/material-experimental). Seems to be close, but unlikely to become the default in 12.0. More details on status in [Angular Components README](https://github.com/angular/components/tree/b8d83cb0f4d990a1cb8a976b2383817b304e4dcd#what-were-working-on-now-q1-2021)

## 🤫 Offer Google engineers better integration with Angular and Google's internal server stack
Internal project. Unlikely to have any public movement or benefits.

## ✅ Streamline releases with consolidated Angular versioning & branching

Some details in [Angular biweekly meeting notes](https://docs.google.com/document/d/1rC5dz7AkCZP813daT_bccbS-20OLmXgBVi50CSKx148/pub) from March 23, 2021. It sounds like there are some difficulties.

This seems to be done. All of the latest releases for Angular CLI, Material, and Core have been released on the same day and the versions are in sync.

## ✅ Optimized build speed and bundle sizes with Angular CLI webpack 5

Opt-in preview available in 11.1 [details here](https://github.com/angular/angular-cli/pull/18820)

[Webpack 5 is now the default](https://github.com/angular/angular-cli/pull/20084) as of 12.0.0-next.9.

One big feature of Webpack 5 is persistent cahes, which you can learn more about [here](https://github.com/angular/angular-cli/issues/21545). It might be turned on by deafult in Angular 13.

## ✅ Higher developer consistency with commit message standardization

No public changes that I know of, but marked as done.

## ✅ Accelerated debugging and performance profiling with Angular DevTools

[Angular DevTools](https://angular.io/guide/devtools) is available with some dope features.

## ✅ Improved developer onboarding with refreshed introductory documentation

I didn't watch this closely, but it's marked as done. You can see the intro docs [here](https://angular.io/guide/what-is-angular)
