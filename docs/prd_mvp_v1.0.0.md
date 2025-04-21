# Product Requirements Document – StreamHub MVP v1.0

## Overview

StreamHub is a desktop IPTV player focused on simplicity, speed, and casting support. This MVP aims to provide a functional base for live TV, movies, and series playback.

## Scope

This document describes the core features for the MVP. Secondary features (offline mode, notifications, settings panel, etc.) are excluded for this version.

| Requirement ID | Description                                 | User Story                                                                               | Expected Behavior/Outcome                                                                            |
| -------------- | ------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| REQ-001        | User connection to IPTV                     | As a user, I want to enter my IPTV credentials to access my content                      | The user can input their M3U URL or Xtream Codes credentials and connect successfully                |
| REQ-002        | Home interface with quick access            | As a user, I want to see the Live TV, Movies, Series, and Catch-up sections upon opening | The homepage displays the four main categories                                                       |
| REQ-003        | Content search                              | As a user, I want to search for specific content within the selected category            | The user can search for content by title, genre, or other metadata                                   |
| REQ-004        | Add to favorites                            | As a user, I want to add channels, movies, or series to my favorites                     | The user can add or remove items from their favorites list                                           |
| REQ-005        | Continue watching                           | As a user, I want to resume watching from where I left off                               | The last playback position is saved and displayed upon relaunch                                      |
| REQ-006        | Content categorization by genre, type, etc. | As a user, I want to see my movies and series sorted by category                         | The app dynamically retrieves and displays categories based on available data from the IPTV provider |
| REQ-007        | Viewing history                             | As a user, I want to see my viewing history                                              | The app keeps a record of recently watched content                                                   |
| REQ-008        | Chromecast support                          | As a user, I want to cast my content to my TV                                            | The app supports casting via Chromecast and AirPlay                                                  |

<!-- | REQ-012 | User settings management | As a user, I want to modify my account settings | The user can change their password, email, and notification preferences | -->

<!-- | REQ-008        | Content update notifications                | As a user, I want to be notified about new available content                             | The app sends push notifications for new movies and series                                           | -->

<!-- | REQ-009        | Multi-language support                      | As a user, I want to change the app's language                                           | The app supports at least English and French                                                         | -->

<!-- | REQ-009 | Multi-language support | As a user, I want

<!-- | REQ-010 | Offline mode | As a user, I want to access my favorites without an internet connection | Favorites are stored locally and accessible offline | -->

<!-- | REQ-011 | User settings management | As a user, I want to modify my account settings | The user can change their password, email, and notification preferences | -->
