Expose Ansible Tower AWS Keys
=============================

![CI](https://github.com/deekayen/ansible-tower-aws-keys/workflows/CI/badge.svg) [![Project Status: Concept – Minimal or no implementation has been done yet, or the repository is only intended to be a limited example, demo, or proof-of-concept.](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept)

Amazon Web Services CLI access keys are encrypted at rest in Ansible Tower, but they need to be loaded at runtime to authenticate using boto to AWS. That gives you an opportunity to print the keys to your console if you need a reminder of what they are.

![](images/AWS_key_printer_template.png)


![](images/AWS_key_printer_log.png)
