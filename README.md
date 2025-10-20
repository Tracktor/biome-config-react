# @tracktor/biome-config-react

🧹 **Shared Biome configuration for Tracktor React projects**.  
This package provides a centralized and consistent linting and formatting setup using [Biome](https://biomejs.dev/), ensuring clean and maintainable code across all Tracktor front-end applications.

---

## 📦 Installation

```bash
bun add -D @biomejs/biome @tracktor/biome-config-react
# or
yarn add -D @biomejs/biome @tracktor/biome-config-react
# or
npm install -D @biomejs/biome @tracktor/biome-config-react
```

## ⚙️ Usage

Create or update a biome.json (or biome.jsonc) file at the root of your project:

```JSON
{
  "extends": ["@tracktor/biome-config-react"]
}
```

## 🧭 Commands

Check for linting and formatting issues:

```bash
bun x biome check .
```

Automatically fix issues:

```bash
bun x biome check . --write
```

Format files:

```bash
bun x biome format . --write
```
