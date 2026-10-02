<p align="center"><img src="qompare.svg" alt="Qompare logo" width="88"></p>
<h1 align="center">Qompare</h1>
<p align="center">Supplier quotes, compared in one private desktop workspace.</p>
<p align="center"><strong>Windows 10/11 · Free Testing Demo · Proprietary software</strong></p>

## From supplier PDFs to a clearer purchasing decision

Purchasing teams often copy information from several supplier PDFs into Excel before they can compare offers. Qompare brings that information together so you can review prices, specifications and commercial terms side by side.

This is an early testing release. We are looking for people who regularly compare supplier offers to tell us whether it reduces manual work and shows the information they need to make a decision.

## What it does

- Compare **2–5 text-based PDF quotes** in one workspace.
- Review prices, quantities, delivery times, payment terms and minimum order quantities.
- Highlight the lowest verified quoted cost and available delivery/payment trade-offs.
- Flag major specification conflicts, secondary differences and missing information.
- Compare currencies with **manually entered exchange rates**.
- Prepare supplier clarification questions from missing details.
- Save comparisons automatically and search local history.
- Process supplier documents locally on your computer.
- Use the interface in **English, Czech, Slovak, German, Italian or Spanish**. Supplier document text remains in its original language.

## Download

**[Download Qompare Testing Demo 0.3.3 for Windows](https://qompare-pilot.czesmokie.workers.dev/downloads/Qompare_0.3.3_x64-setup.exe)**

The installer is approximately **983 MB** because local document processing is included. No activation key or separate processing service is required.

Use 64-bit Windows 10/11 with at least 8 GB RAM and 3 GB available disk space. Install for your current Windows user, create a local account, then open **New comparison**. The last signed-in account is remembered; sign out on a shared computer.

Updates are available through **Settings → Updates**. Save your work before installing an update.

## Current limits

- Text-based PDFs only; scanned documents and OCR are not supported.
- Up to 15 MB, 30 pages and 24,000 extracted characters per PDF.
- Results can be incomplete. Verify values, specifications and commercial conditions against the original documents before purchasing.
- Missing costs are not assumed to be zero. A low price does not by itself establish the best supplier.
- The Windows installer does not yet have a publisher certificate and may trigger SmartScreen.

## Privacy

Supplier PDFs and extracted quote data stay on your computer. Feedback is sent only when you submit it. Usage statistics are optional and off by default. Approximate connection country has its own separate, optional permission; Qompare does not store your IP, city or precise location.

Read [the privacy overview](PRIVACY.md) for the data sent when using online features.

## Help test it

Try it with a few non-sensitive supplier quotes and tell us:

1. Did it extract the important information correctly?
2. Did it make the pricing and commercial trade-offs clear?
3. Did it save time compared with your existing process?
4. What would still make you return to Excel?

Use **Settings → Send feedback** or open a GitHub issue. Do not include confidential quotes, account passwords or company-sensitive information in public issues.

## About this repository

This repository contains public product information and downloadable releases. **Qompare is closed source**; its application source code is not published here. See [NOTICE.md](NOTICE.md).
