# Marktown Concept

## Summary

1. **[User Stories](USER_STORIES.md)**
2. [Project Goals](#project-goals)
3. [Technical Architecture](#technical-architecture)
4. [About Markdown](#about-markdown)

## Project Goals

**1.0**

* Markdown parser
* Editor (buttons for inserting attributes: tables, bold-text, italic-text, ...)
* File browser
* Git storage
* Low system requirements
* Basic full text search

**2.0**

* User authentication and authorization
* Advanced Markdown dialects (think of Graphs, Math, Spreadsheets, ...)
* Advanced search (fuzzy, intelligent, ...)
* Multiple git repositories

**3.0**

* Comments on files/lines per git revisions
* Forks and pull-requests
* Live collaboration
* Publishing
* Storage integration (Dropbox, Github, ...)
* Plugin system

## Technical Architecture

* Storage in Git
* REST backend in Go/Beego for Git abstraction
* Javascript UI for Markdown editor and file browser

## About Markdown

As of today the Markdown language is the defacto standard for documentation in the context of software development. It is just as suitable for writing simple "readme" files as for writing multi-part project documents or even whole books with hundreds of pages.

**Key Advantages**

* Minimal requirements to the editor.
* Human readable on its own.
* Easily versionable (using version control systems like Git).
* Very popular (wide range of tools and integrations).
* Self-contained and portable.

See also [https://github.com/rhythmus/markdown-resources](https://github.com/rhythmus/markdown-resources).
