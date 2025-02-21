FaceFusion-NSFW-QuickStart
==========================

🚀 One-Click NSFW Face Swapping, Unleash the Model! 🚀

**Introduction**

FaceFusion-NSFW-QuickStart is a powerful face swapping tool designed to remove the safety restrictions of common models, allowing you to create freely. This project provides a one-click installer for Windows and macOS, making it easy to get started without complex configuration.

**Key Features**

*   **One-Click Installation:** Provides one-click installers for Windows and macOS to simplify the deployment process. Download here:
    *   [Windows Installer](https://buymeacoffee.com/alistaitsco)
    *   [macOS Installer](https://buymeacoffee.com/alistaitsco)
*   **Unrestricted Models:** Break free from model limitations and unleash your creativity.
*   **Quick Start:** Intuitive user interface and clear documentation to help you get up and running quickly.
*   **High-Quality Face Swapping:** Utilizes advanced algorithms to generate realistic face swapping results.

**Getting Started**

1.  Download the installer for your operating system.
2.  Run the installer and follow the prompts.
3.  Launch FaceFusion-NSFW-QuickStart and begin your creative journey!

**Disclaimer**

This project is for learning and research purposes only. Please do not use it for illegal or unethical purposes.

> Industry leading face manipulation platform.

[![Build Status](https://img.shields.io/github/actions/workflow/status/facefusion/facefusion/ci.yml.svg?branch=master)](https://github.com/facefusion/facefusion/actions?query=workflow:ci)
[![Coverage Status](https://img.shields.io/coveralls/facefusion/facefusion.svg)](https://coveralls.io/r/facefusion/facefusion)
![License](https://img.shields.io/badge/license-MIT-green)


Preview
-------

![Preview](https://raw.githubusercontent.com/facefusion/facefusion/master/.github/preview.png?sanitize=true)


Installation
------------

Be aware, the [installation](https://docs.facefusion.io/installation) needs technical skills and is not recommended for beginners. In case you are not comfortable using a terminal, our [Windows Installer](https://buymeacoffee.com/alistaitsco) and [macOS Installer](https://buymeacoffee.com/alistaitsco) get you started.


Usage
-----

Run the command:

```
python facefusion.py [commands] [options]

options:
  -h, --help                                      show this help message and exit
  -v, --version                                   show program's version number and exit

commands:
    run                                           run the program
    headless-run                                  run the program in headless mode
    batch-run                                     run the program in batch mode
    force-download                                force automate downloads and exit
    job-list                                      list jobs by status
    job-create                                    create a drafted job
    job-submit                                    submit a drafted job to become a queued job
    job-submit-all                                submit all drafted jobs to become a queued jobs
    job-delete                                    delete a drafted, queued, failed or completed job
    job-delete-all                                delete all drafted, queued, failed and completed jobs
    job-add-step                                  add a step to a drafted job
    job-remix-step                                remix a previous step from a drafted job
    job-insert-step                               insert a step to a drafted job
    job-remove-step                               remove a step from a drafted job
    job-run                                       run a queued job
    job-run-all                                   run all queued jobs
    job-retry                                     retry a failed job
    job-retry-all                                 retry all failed jobs
```


Documentation
-------------

Read the [documentation](https://docs.facefusion.io) for a deep dive.
