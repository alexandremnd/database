# Profilarr Config - French Torrent Community 🇫🇷

A [Profilarr](https://github.com/Dictionarry-Hub/profilarr) configuration database tailored for the **French torrent community**.

## About

This repository provides a Profilarr-compliant database built on top of [Dictionarry](https://dictionarry.dev) rules. It contains custom formats, quality profiles, and media management settings optimized for French torrent releases.

## How It Works

This config leverages **Dictionarry rules** with **regex patterns** to accurately identify and score media releases. The regex patterns are designed to:

- Match French-specific release naming conventions
- Identify audio/video codecs, HDR formats, and quality tiers
- Score releases based on preferred attributes (Remux, WEB-DL, Atmos, etc.)

## Structure

- `custom_formats/` - Custom format definitions for Radarr/Sonarr
- `regex_patterns/` - Regex pattern rules used by Dictionarry
- `profiles/` - Quality profile configurations
- `media_management/` - Naming conventions and quality definitions
- `templates/` - Reusable configuration templates

## Usage

Link this database to your Profilarr instance following the [Profilarr Database Setup Guide](https://dictionarry.dev/profilarr-setup/linking?section=database-spotlight).

## Resources
- [Dictionarry Documentation](https://dictionarry.dev)
- [Profilarr Repository](https://github.com/Dictionarry-Hub/profilarr)
- [Dictionarry Discord](https://discord.com/invite/Y9TYP6jeYZ)
