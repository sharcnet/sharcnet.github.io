[![GitHub Pages Deploy](https://github.com/sharcnet/sharcnet.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/sharcnet/sharcnet.github.io/actions/workflows/deploy.yml)
# SHARCNET Web Sandbox

# Dependency

- [HUGO](https://gohugo.io/installation/) `0.114.0` or higher

## Working with the Sandbox

```bash
git clone https://github.com/sharcnet/sharcnet.github.io.git
cd sharcnet.github.io
npm install
hugo server -w
```

## Generate in the `public` folder

```bash
hugo --gc --minify
```

## Adding content

```bash
hugo new content/posts/example.md
```
