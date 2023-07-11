# Contribution Guidelines

Most of *eProsima*'s products follow an open source model.
As such, we are always listening to the community for issues, feature improvements and suggestions.

## Contributions Licensing

Any contribution that you make to this repository will be under the Apache 2 License, as dictated by that [license](LICENSE):

~~~
5. Submission of Contributions. Unless You explicitly state otherwise,
   any Contribution intentionally submitted for inclusion in the Work
   by You to the Licensor shall be under the terms and conditions of
   this License, without any additional terms or conditions.
   Notwithstanding the above, nothing herein shall supersede or modify
   the terms of any separate license agreement you may have executed
   with Licensor regarding such Contributions.
~~~

## Developer Certificate of Origin

Contributors must sign-off each commit by adding a `Signed-off-by: ...` line at the end of commit messages.
This certifies that they have the right to submit the code they are contributing to the project according to the [Developer Certificate of Origin (DCO)](https://developercertificate.org/).
Pull requests with unsigned commits will not pass the automated checks until unsigned commits have been amended.

## Issues and Support

*eProsima* developers welcome all contributions, and we will be grateful if you follow the guidelines below while contributing to the different projects.
User issues are classified in the following categories.
Please, help us giving you a better support by opening your issue in the corresponding  category of the corresponding repository.

### Issues

Issues are understood as bug reports and may be opened by anyone.
Consequently, this section handles malfunctions in the current documented behavior of the product or non-compliances to the DDS specification.
If you are unsure on whether your experienced behavior falls into this category, please open a ticket in the [Support](#support) discussion forum and, if it is a malfunction, an issue will be opened on your behalf with the provided report.

It is appreciated if all related information is provided so the issue may be reproduced.
Otherwise, more information could be required in order to reproduce and solve the issue.
If this is the case, the issue will be labeled with `need more info`.
Please, be advised that in case that no response is received within a month, the issue would be closed due to inactivity.
The issue may be reopened if the required information is provided.

### Feature request

Feature requests and improvements suggestions should be opened in the Ideas discussion forum.
Please, remember to select the corresponding category while opening the discussion.
It is also encouraged to contact directly with [eProsima support team](#getting-help) for a feature evaluation.

### Q&A

Questions about an *eProsima* product behavior and features should be opened in the corresponding repository's Q&A (Questions & Answers) discussion forum.
Please, remember to select the correct category while opening the discussion.
It is strongly advised to first consult the *eProsima* product related documentation and previous Q&A in the forum.

### Support

Most user issues would fall in this category.
*eProsima* products provide a lot of features and tuning for optimal behavior for each use case, and this may not be an easy task.
These issues should be opened in each product Support discussion forum.
Please, remember to select the corresponding category while opening the discussion.

## Submitting a pull request

If writing an issue does not do it for you because you just know what has to be done and how, and you have the energy and time to directly contribute to the project, submitting a pull request is your way to go.
Please mind that by doing so, you accept to abide to the pull request process followed by eprosima, meaning:

1. Modify one feature at a time.
   Avoid pull requests where several features or functionalities are implemented or modified at the same time.
   If you have many contributions, please split them in different pull requests.
1. Submit your pull requests in separate branches.
   As for branch names, we normally use `feature/*` for adding functionality or refactors, `hotfix/*` for small fixes, and `bugfix/*` for larger parts that do not reflect reality and need to be corrected.
1. Code should be formatted according to our [Code Style Guide](https://github.com/eProsima/code-style).
   We also provide an [uncrustify](https://github.com/uncrustify/uncrustify) configuration file to help in that regard.
1. Test your changes before submission, and only submit "green" pull requests.
   Our Continuous Integration will still run the tests, but this way the process becomes smoother and the "Fixing errors" commits and re-runs are avoided.
   If you need any help setting up, please let us know by opening an issue.
   We will be happy to help you and also to improve the instructions for any repository if needed.
1. Be prepared to receive criticism, and potentially tons of change requests.
   Please do not take criticism as personal, we really appreciate your contributing effort.
   To be merged into the master branch or the releases, a pull request must be approved by at least one reviewer with write access.
1. Changes of the kind `feature/*` must be accompanied by a pull request to the appropriate documentation repo documenting the added functionality.
1. Mind that [LICENSE](LICENSE) applies to all contributions made to this repository.

## Getting Help

If you need support you can reach us by mail at `support@eProsima.com` or by phone at `+34 91 804 34 48`.
