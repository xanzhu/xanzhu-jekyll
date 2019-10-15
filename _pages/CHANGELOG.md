---
layout: page
permalink: changelog/
title: XANZHU CHANGLOG
excerpt: Information about updates and changes towards our domain. 
---

# XANZHU CHANGLOG
Information about updates and changes towards this domain. CDN changelog listed until we move that over to our subdomain directly.  
Updated every so often (Weekly)

## 0.3 - Preview / v2
- Testing CircleCI Intergration!

## 0.0.3 - October 10th 2019
### Added
- Markdown support (Beta)
- New _pages directory within jekyll
- Default Jekyll markdown settings to config.yml (Testing)
- New head file for posts (Pages)
- More internal scripts for xdde to make things easier

### Fixed
- Fixed favicon url 

----

# CDN Network

## 1019.2 - October 8th 2019
### Security
- Externally hosted files are now in their own directory. This prevents the entire directory being leaked when scanning the domain. 

### Changed
- Cleaned up website design formatting to follow a darker theme
- Changed d2 > A2 in terms of the directory

### Added
- New Banner logo
- Internal directory to host all assets used internally

### Fixed
- Cache system, now correctly caches all the new files in the directory. Allowing us to purge cache from the domain without effecting A2 directory
- All urls which used the old d2 directory. 

----

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).