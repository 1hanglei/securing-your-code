
<h1 align="center">Securing your code with GitHub</h1>

<h5 align="center"><a href="https://github.com/joshjohanning">@joshjohanning</a> <a href="https://github.com/mickeygousset">@mickeygousset</a>
<a href="https://github.com/writingpanda">@writingpanda</a>
<a href="https://github.com/felickz">@felickz</a>
<a href="https://github.com/tspascoal">@tspascoal</a>
</h5>

<p align="center">
  <a href="#workshop-labs">Workshop Labs</a>
  <a href="#book-resources">Resources</a>
</p>

- **Who is this for**: Enterprise - Engineering Leadership, Enterprise - Developers, Open Source Developers or Maintainers, Security Professionals, Startups, Security Leadership, Educators
- **What you'll learn**: Here at GitHub, we like to say that "found means fixed." That's because when issues are found they can more easily be fixed. In this workshop you'll dive into a repository filled with security alerts and begin to remediate them using GitHub Advanced Security (GHAS) and Dependabot, effectively maintaining code integrity. You'll also encounter and resolve a few security issues using Copilot Autofix. The end goal? To learn and develop strategies to motivate your developers to turn reactive fixes into proactive security habits.


See [requirements](_labs/requirements.md) to see what is needed to run this lab.

---

## Workshop Labs

### Lab 1 - GitHub Advanced Security Feature Introduction

This lab will introduce you to GitHub Advanced Security (GHAS) and its features.

- Get started here - [Lab 1](./_labs/lab1.md)

---

### Lab 2 - Reviewing and Managing Security Alerts

This lab will show you how to review and managed the alerts created in Lab 1.

- Get started here - [Lab 2](./_labs/lab2.md)

---

### Lab 3 - Hands-on with Code Scanning

This lab will have you add some bad code, utilize repository rulesets to block the code, and Copilot Autofix to fix the code.

- Get started here - [Lab 3](./_labs/lab3.md)

---

### Lab 4 - Hands-on with Dependency Review

This lab will have you utilize the Dependency Review action to stop a bad vulnerability in a pull request.

- Get started here - [Lab 4](./_labs/lab4.md)

---

### Lab 5 - Hands-on with Secret Scanning

This lab will have you utilize Secret Scanning with Push Protection to prevent secrets from entering the codebase.

- Get started here - [Lab 5](./_labs/lab5.md)

---

### Lab 6 - Hands-on with Security Overview

This lab will teach you how to effectively use the Security Overview to review and alerts and coverage in an organization.

- Get started here - [Lab 6](./_labs/lab6.md)

---


### Extra Credit: Advanced CodeQL Setup

This open-ended extra credit lab will have you switch to the advanced CodeQL setup.

- Get started here - [Extra Credit Lab 1](./_labs/lab7-ec.md)

---

### Extra Credit: Custom Patterns for Secret Scanning

This open-ended extra credit lab will have you create a custom secret scanning pattern.

- Get started here - [Extra Credit Lab 2](./_labs/lab8-ec.md)

---

## :book: Resources

- [GitHub Docs - About GitHub Advanced Security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security)
- [GitHub Security Learning Pathway](https://resources.github.com/learn/pathways/security/)


## License 

### Securing your code with GitHub

This project is licensed under the terms of the MIT open source license. Please refer to [MIT](./LICENSE) for the full terms.

### OWASP Juice Shop

This lab uses and includes sample code from the OWASP Juice Shop project. The Juice Shop is Copyright (c) 2014-2024 Bjoern Kimminich & the OWASP Juice Shop contributors. Please refer to the [LICENSE](./LICENSE) for the full terms.

---

## Attachments provided

Two attachments were provided to this session and are included in the PR for reference:
- pubspec.yaml (C:\Users\ling\.copilot\attachments\94fae2bf-eea1-49d9-9f43-d57332c251a9-pubspec.yaml)
- README.md (C:\Users\ling\.copilot\attachments\cf51bc5b-f07f-4665-ae93-bf70f039915e-README.md)

Decision and reconciliation

- Repository type: this project is a GitHub security workshop (not a Dart/Flutter app). There is no pubspec.yaml in the repository root and the codebase is not structured as a Flutter project. Therefore the attached pubspec.yaml is not applicable and was not merged into the codebase.
- The attached README.md documents a separate Flutter app (overseas_guide). Relevant guidance has been summarized here for future use: to apply it, create a new Flutter project, replace its `lib/` folder and `pubspec.yaml` with the attached files, run `flutter pub get`, and `flutter run` on a connected device or emulator.

If the maintainers want the Flutter project added to this repository, open an issue or reply to this PR and the attachments will be integrated as a new subproject.

Verification

- No runtime or test changes were required by these documentation updates. Available JS package tests/builds were not impacted by the README-only change.

---

