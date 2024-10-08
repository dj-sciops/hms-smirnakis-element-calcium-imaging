# Changelog

Observes [Semantic Versioning](https://semver.org/spec/v2.0.0.html) standard and
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/) convention.

## [0.3.0] - 2024-10-08

- Fix - Fix diameter calculation in `FieldProcessing` table

## [0.2.0] - 2024-06-10

- Feature - Add diameter and aspect ratio params computation in `FieldProcessing` table
- Update - all occurrences of `datetime.utcnow()` to `datetime.now(timezone.utc)`.

## [0.1.0] - 2024-06-06

- Feature - Pull from upstream staging for image processing / segmentation on a per-field basis
