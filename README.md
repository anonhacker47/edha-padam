# Edha Padam

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Creative Commons License](https://img.shields.io/badge/License-CC%20BY--NC--SA%203.0-lightgrey.svg)
![ODC Attribution License](https://img.shields.io/badge/License-ODC%20By-brightgreen.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue.svg)
![React](https://img.shields.io/badge/React-19.1-blue.svg)
![WebGL](https://img.shields.io/badge/WebGL-enabled-green.svg)

## 🎬 Overview

**Edha Padam** is an interactive WebGL gallery exploring the world of Malayalam cinema. It visualizes **1,702 film posters** in an interactive force-directed voronoi diagram, allowing users to discover and explore the rich history of Malayalam movies.

This project is a fork of [nothing-to-watch](https://github.com/gnovotny/nothing-to-watch), refactored and customized for Malayalam movie data.

### Key Features

- **Interactive WebGL Visualization**: Real-time rendering of over 1,700 Malayalam film posters.
- **Custom Voroforce Engine**: Purpose-built force simulation and rendering system.
- **Deep Data**: Includes metadata (titles, years, genres) for a vast collection of Malayalam films.
- **Responsive Design**: Adapts to desktop, tablet, and mobile devices.
- **Performance Optimized**: GPU-accelerated rendering with efficient texture compression (KTX).
- **Film Discovery**: Explore movies through visual relationships and clustering.

## 🚀 Quick Start

### Prerequisites

- **Bun** (recommended) or Node.js 18+
- Modern browser with WebGL 2.0 support

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd edha-padam
   ```

2. **Set up environment variables**
   ```bash
   cp .env.local.example .env.local
   ```

3. **Install dependencies**
   ```bash
   bun install
   ```

4. **Start development server**
   ```bash
   bun dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 🛠 Development

### Available Scripts

| Command | Description |
|---------|-------------|
| `bun dev` | Start development server |
| `bun build` | Build for production |
| `bun preview` | Preview production build |

### Architecture

- **React 19** with TypeScript and Vite
- **Tailwind CSS**
- **Zustand** for state management
- **Voroforce Engine**: Custom WebGL engine using OGL and GLSL shaders

### Data & Assets

- **Film Data**: JSON files in `public/json/` (Chunked data)
- **Images**: KTX compressed textures in `public/media/` (High/Mid/Low LODs)
- **Source Images**: Original JPEG posters in `public/media/single/`

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

**Exceptions**:
- WebGL fragment shaders: Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License.
- Film data: Open Data Commons Attribution License (ODC-By) v1.0.

## 🤝 Credits

Based on the [nothing-to-watch](https://github.com/gnovotny/nothing-to-watch) project.
Refactored for Malayalam cinema by the Edha Padam team.
