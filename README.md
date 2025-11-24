# lawlorse-final-year-project
# ECH Test Setup Project - Bi-Weekly Timeline

This project aims to set up and test **Encrypted ClientHello (ECH)** on a Lighttpd web server to evaluate privacy and functionality. Below is the planned schedule of tasks and deliverables in two-week increments.

Period            Goals / Deliverables                                             Notes
-----------------------------------------------------------------------------------------------------------
Oct 14–27         - Begin learning LaTeX basics                                    Focus on environment setup and version control workflow
                  - Set up working environment (Ubuntu, GCC, CMake, Git)

Oct 28–Nov 10     - Study ECH protocol in detail                                   Start simple diagrams or notes in LaTeX
                  - Test basic TLS setup and certificates
                  - Research and understand test harness design for ECH
                  - Document initial setup in LaTeX

Nov 11–24         - Enable ECH on Lighttpd                                         Achieve a working proof-of-concept
                  - Capture test results with bssl client / openssl
                  - Upload initial results to GitHub

Nov 25–Dec 8      - Test ECH with multiple browsers (Chrome, Firefox)              Include screenshots and command outputs
                  - Introduce Playwright for automated headless browser tests
                  - Validate ECH negotiation inside real browser stacks
                  - Update LaTeX documentation

Dec 9–22          - Basic performance measurements                                 Prepare charts/graphs for results
                  - Expand Playwright tests to capture timing and errors
                  - Begin structured LaTeX report

Dec 23–Jan 5      - Mid-project review: summarize progress                         Create a short PDF report in LaTeX
                  - Update GitHub with configs, scripts, and Playwright tests

Jan 6–19          - Refine ECH setup and browser tests                             Keep GitHub updated with commits
                  - Add Playwright trace recording, screenshots, and logs
                  - Fix server issues or test failures

Jan 20–Feb 2      - Finalize ECH implementation on Lighttpd                        Start organizing final report structure
                  - Automate recurring tests using Playwright (CI-compatible)
                  - Improve reporting of handshake outcomes in logs

Feb 3–16          - Run comprehensive ECH tests and collect results                Include methodology, results, and analysis
                  - Compare bssl client vs Playwright browser behaviour
                  - Draft full LaTeX report

Feb 17–Mar 1      - Review and refine LaTeX report                                 Ensure clarity and reproducibility
                  - Add figures, tables, browser traces, and diagrams

Mar 2–15          - Supervisor feedback and revisions                              Clean up repo and LaTeX PDF
                  - Finalize Playwright automation scripts and documentation

Mar 16–29         - Prepare project presentation and demo                          Keep slides concise and demo reproducible
                  - Test demo setup (show Lighttpd + Playwright interaction)

Mar 30–Apr 12     - Submit final report and deliverables                           Ensure GitHub repo and LaTeX PDF are finalized
                  - Stretch Goal: Submit pull request to Lighttpd repository
                  - Present project
