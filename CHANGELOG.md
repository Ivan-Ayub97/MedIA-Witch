# Changelog for MedIA-Witch

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added

- **Full integration with QualityScaler**'s capabilities for both image and video upscaling.
- Support for upscaling videos using AI models (Real-ESRGAN, ESRGAN, SRGAN, BSRGAN).
- Batch processing support for both images and videos.
- Integration with FFmpeg for video encoding/decoding and format conversion.
- Enhanced AI model options for better quality upscaling (Real-ESRGAN, ESRGAN, SRGAN, BSRGAN).
- Option to customize output resolution, aspect ratio, and formats (JPEG, PNG, MP4, MOV, etc.).
- New advanced settings for controlling AI model parameters for finer control over the upscaling process.

### Fixed

- Fixed UI issue where images would not display correctly after being processed.
- Resolved memory leak issues during batch processing of large files.
- Improved the stability of the video upscaling feature, reducing crashes during large video processing.
- Fixed minor bugs in the progress bar during upscaling operations.

## [1.0.0] - 2025-02-18

### Added

- Initial release of **MedIA-Witch** based on **QualityScaler**.
- Full support for image upscaling with AI models (Real-ESRGAN, ESRGAN, SRGAN, BSRGAN).
- Video upscaling powered by **QualityScaler**'s integration with AI models and FFmpeg.
- Batch processing for upscaling both images and videos, optimizing processing time for large collections.
- Customizable output formats for images and videos, including support for PNG, JPG, JPEG, MP4, and more.
- Support for **IRCNN** for even higher-quality upscaling.
- User-friendly interface with dark mode (black background and green text).
- Open-source release under the MIT License, encouraging community contributions.

### Fixed

- Optimized image loading and upscaling performance.
- Improved video frame handling, preventing frame drops during upscaling.
- Fixed minor user interface bugs to ensure smoother interactions.s

## [0.1.0] - 2025-01-10 (Pre-release)

### Added

- Basic AI-powered image upscaling using **QualityScaler**'s Real-ESRGAN model.
- Initial design of the graphical user interface (GUI) for easy interaction with the software.
- Basic batch processing for multiple images at once, reducing time spent on manual upscaling.
- Packaging for distribution as a pre-release version.

### Changed

- Significant updates to the image upscaling logic for better performance and compatibility with video upscaling.

### Fixed

- Fixed bugs related to image rendering and UI display issues.
- Improved initial batch processing functionality, addressing stability problems.

---

## How to read the changelog

- **Added**: New features and capabilities added to the software.
- **Changed**: Modifications to existing functionality.
- **Fixed**: Bug fixes and patches.
- **Deprecated**: Features that are no longer supported.
- **Removed**: Features or functionality that has been removed from the software.
- **Security**: Important security fixes or improvements.
