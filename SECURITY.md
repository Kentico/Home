# Kentico Open Source Security Policy

This document outlines security procedures and general policies for the
Kentico Open Source projects as found on <https://github.com/Kentico>

## Reporting a Vulnerability

Kentico and our community take all software security vulnerabilities seriously. We truly appreciate your efforts for responsible disclosure and will make every effort to acknowledge your contributions to fix reported issues. If you believe you have found a security vulnerability in any Kentico-owned repository, please report it by emailing our security team at:

    security@kentico.com

Do not disclose it as a public issue. This gives us time to work with you to fix the issue before public exposure, reducing the chance that found vulnerability will be exploited before a patch is released.

After the initial response to your report, the security team will make sure to keep you informed of the progress toward a fix and full announcement. When reporting a vulnerability, please remember to include the following information (the more, the better) to help us better understand the nature and scope of the issue:

* Issue type (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
* Step-by-step instructions to reproduce the issue with relevant code snippets
* Full paths of source file(s) related to the manifestation of the issue
* Any special configuration required to reproduce the issue
* Impact of the issue, including how an attacker might exploit the issue

This information will help us understand your report and fix the vulnerability faster. If we are not able to reproduce the reported issue, we may also ask for additional information or guidance. To ensure a timely response to your report, please ensure that the entirety of the report is
contained within the email body and not solely behind a web link or an attachment.

## Configuration settings

Note that our responsibility doesn't apply to configuration weaknesses. We encourage you to use best practices when configuring your application/database and put great emphasis on role-based access control to provide a safe environment. We consider our application to be secure-by-default, so please understand that reported security vulnerabilities will be tested and reproduced using settings that we consider to be safe. For more information, visit our documentation <https://docs.xperience.io/xp>

## Vulnerabilities in third-party modules

If you find any security vulnerabilities in third-party modules that we use, please report it to the maintainer of that module. If you discover that we are using third-party modules with a deprecated version or that we are using modules in an insecure way and you believe it could be a potential
security vulnerability, don't hesitate to contact us.

## Comments on this Policy

If you have any suggestions on how to improve this file/process, please submit a pull request.
