---
title: Privacy Policy
---

# Privacy Policy

_Last updated: 28 October 2026_

## 1. Overview

Acorn Sheets Reader is a small Python utility for researchers to read Google Sheets data in their own analysis workflows.

## 2. Google account data accessed

The application uses Google OAuth 2.0 and requests the following permission:

`https://www.googleapis.com/auth/spreadsheets.readonly`

This permission allows the application to read spreadsheet contents that the signed-in Google account is authorized to access.

## 3. How data is used

Google account authorization is used to authenticate the researcher and make Google Sheets API requests.

Spreadsheet values returned by the API are used by the researcher's Python script. They may be processed in the researcher's local environment or computing environment according to their own analysis workflow.

## 4. Storage and sharing

OAuth credentials are stored in a local token file associated with the researcher's user account. Users are responsible for protecting that file and their computing account.

The application maintainer does not operate a central server for collecting spreadsheet contents or OAuth tokens. The application does not intentionally transmit spreadsheet contents to the maintainer.

Google processes information as necessary to provide its APIs and OAuth services under Google's own privacy terms.

## 5. Data retention and deletion

The researcher can remove their local OAuth token file to delete the locally stored authorization credentials. They can also revoke the application's access through their Google Account security settings.

Spreadsheet data saved by the researcher's own scripts, notebooks, or analysis tools is managed separately by that researcher.

## 6. Security

Users should protect their computing accounts, avoid sharing token files, and avoid committing credentials or spreadsheet data to public repositories.

No method of electronic storage or transmission can be guaranteed to be completely secure.

## 7. Changes to this policy

This policy may be updated if the application's functionality or data practices change.

## 8. Contact

For questions about this utility or this policy, contact:

kbiriukov.tsu@gmail.com
