This tool is a prequel to our authentication solution. It streamlines the onboarding of new users, the creation of varied authentication links and the tracking of these links.

**Table of Contents**

- [Project Setup](#project-setup)
  - [Pre-requisites](#pre-requisites)
    - [Pre-commit](#pre-commit)
  - [Installation](#installation)
  - [Compiles and hot-reloads for development](#compiles-and-hot-reloads-for-development)
  - [Compiles and minifies for production](#compiles-and-minifies-for-production)

## Project Setup

### Pre-requisites

#### Pre-commit

The project uses `pre-commit` for identifying and fixing simple issues before you even make a commit.

1. Install pre-commit
   Use `pip` to install pre-commit

   ```sh
   pip install pre-commit
   ```

   Or using homebrew on macOS

   ```sh
   brew install pre-commit
   ```

   For more installation alternatives, check out [Pre-commit official documentation](https://pre-commit.com/#install).

2. Verify pre-commit installation
   ```sh
   pre-commit --version
   ```

### Installation

```
npm install
pre-commit install
```

### Compiles and hot-reloads for development

```
npm run dev
```

### Compiles and minifies for production

```
npm run build
```
