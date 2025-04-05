# ElectronJS with React & TS

Status: Draft
Category: Guide
Last edited time: April 5, 2025 12:00 PM
Author: Fahad 
Sub-item: Basic Setup (https://www.notion.so/Basic-Setup-1c025c8b3536802b88b1d4a75e15d12a?pvs=21), Define TS Config (https://www.notion.so/Define-TS-Config-1c025c8b353680298eead7ca193bec49?pvs=21), Setup Dev tools (https://www.notion.so/Setup-Dev-tools-1c025c8b3536802e8f16d28b821e6415?pvs=21), Setup Electron Builder (https://www.notion.so/Setup-Electron-Builder-1c025c8b35368083b775f09720e67d48?pvs=21)

## 🎯 Overview

ElectronJS is a  JS Framework based on NodeJS & Chromium Engine to develop desktop app. It uses Chromium engine for rendering views and NodeJS for file handling and other OS activities. It uses IPC Event bus as a bridge to communicate between two separate environment.

We can use vanilla HTML CSS & JS to work as entry point of views and use them inside electron project. But as the project grows it becomes hard to maintain.

## ⚡ A Better approach

- Instead of vanilla HTML, CSS & JS we will use ReactJS for rendering views
    - We will use vite as frontend build tool
- Instead of JS we will use TS.
    - Vite will help to transpile TS files related to views (React) while bundling.
    - But we can’t do that for ElectronJS codes. Because we have to organize this TS file with separate arrangement.

## 📋 ElectronJS Setup Guide

We will do this in 4 major steps.

- [x]  Basic Setup
- [x]  Define TS Config
- [x]  Setup Electron builder
- [x]  Setup development tools