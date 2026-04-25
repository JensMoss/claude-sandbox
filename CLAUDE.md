# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

Learning environment for exploring Claude Code capabilities. No build system, tests, or application code — this repo exists to practice and experiment with Claude Code features, workflows, and integrations.

## Auto-commit Hook

A `PostToolUse` hook in `.claude/settings.json` automatically stages, commits, and pushes any file created or edited via the `Write` or `Edit` tools. Commit messages are generated as `Update: <changed files>`. This means every file change is immediately pushed to the remote — be deliberate about what you write or edit here.
