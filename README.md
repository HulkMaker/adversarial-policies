[![Build Status](https://travis-ci.com/HumanCompatibleAI/adversarial-policies.svg?branch=master)](https://travis-ci.com/HumanCompatibleAI/adversarial-policies)

Preliminary research investigating adversarial policies: given a victim policy 
in a multi-agent system, find a policy which will break the victim.

# Setup

This codebase assumes Python 3.6. Install the requirements in 
`requirements-build.txt` before those in `requirements.txt`.
Anaconda users can install directly with `conda env create -f environment.yml`.

# Contributions

Please run the `ci/code_checks.sh` before committing. This runs several linting steps.
These are also run as a continuous integration check.
