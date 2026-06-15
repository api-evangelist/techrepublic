---
title: "Malicious Hugging Face Models Could Trigger Remote Code Execution"
url: "https://www.techrepublic.com/article/news-hugging-face-transformers-rce-flaw/"
date: "2026-06-05"
author: "Ken Underhill"
feed_url: "https://www.techrepublic.com/feed/"
---
A critical vulnerability in Hugging Face Transformers (CVE-2026-4372) allows attackers to execute malicious code when users load poisoned AI models, bypassing security safeguards and potentially exposing cloud credentials and API tokens. The flaw affects multiple library versions when the optional kernels package is installed, and researchers demonstrated that one poisoned field in a model's config.json silently executes arbitrary code without warning. Organizations are advised to update their software and implement stricter access controls for third-party AI models.
