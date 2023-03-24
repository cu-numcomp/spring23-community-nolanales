# Community Software Analysis Proposal

## Software: XiTorch

*Write a paragraph describing what the software does and who its
primary audience is.*
XiTorch is a PyTorch-based differentiable computing library that aids with machine-learning, numerical-calculations, scientific-computing, and linear-algebra. According to their site, "xitorch is a PyTorch-based library of differentiable functions and functionals that can be widely used in scientific computing applications as well as deep learning". The main modules are optimize, integrate, linalg, and interpolate, with various function making up each module. 

### Stats

| Description | Xitorch is a PyTorch-based library of differentiable functions and functionals that can be widely used in scientific computing applications as well as deep learning. |
|---------|-----------|
| Repository URL |  https://github.com/xitorch/xitorch  |
| Main/documentation website |  https://xitorch.readthedocs.io/en/latest/  |
| Year project was started | First Commit January 30, 2020  |
| Number of contributors in the past year | 2 contributors in the last year |
| Number of contributors in the lifetime of the project | 5 total contributors |
| Number of distinct affiliations | >10 |
| Where do development discussions take place? | Not sure  |
| Typical number of emails/comments per week? |  Not sure |
| Typical number of commits per week? | ~5.4 commits per week |
| Typical commit size | Typically 1-3 file changes per commit |
| How does the project accept contributions? | Pull requests via GitHub. There is also an "issues" page on their documentation website.   |
| Does the project have an automated test suite? | no |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [X] I have installed the software
- [ ] I have run at least one example
- [ ] I have run the test suite
- [ ] The test suite passes

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

- No build badge: There is continuous integration, but it looks like the tests are being sent to another library, testPy, and there is no visible build test badge.
- Unsure how they communicate: we are not sure how the creators are communicating, as there have only been two contributors in the last year, and we are not sure how they talk and make decisions during development.
- GitHub repo has some tests not passing: In the last commit, it looks like there were some errors with the build, although they don't appear to be fatal errors. 

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
